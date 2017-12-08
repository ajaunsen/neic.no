[![License](https://img.shields.io/badge/license-%20MPL--v2.0-blue.svg)](../master/LICENSE)

# Sources behind [https://neic.no](https://neic.no)

## How to update the neic.no website

### Short version
We use GitHub pages. Sources are at https://github.com/neicnordic/neic.no.
The web is full of [guides and tutorials](http://lmgtfy.com/?q=github+pages+howto).
GitHub pages uses [GitHub flavored markdown syntax](https://help.github.com/categories/writing-on-github/).
Go to [#web](http://neic.slack.com/messages/web) in NeIC slack if you need someone to talk to.

#### Tips
* Ideally content should be in Markdown files.
* Page layout should be in html files.
* Ideally (almost) no content should be in html files.
* News pictures should be ideally be 762x507 px in size.
* Work locally ([cf below](#work-locally)).
* Show your changes to others at YOURNAME.github.io/neic.no ([cf below](#show-your-changes-to-others)).

### You need
A [GitHub](https://github.com/) account.

Optional: For very minor things like updating an email address it's easiest if
you are part of the [neicnordic](https://github.com/neicnordic) organization.
Ask in [#web](http://neic.slack.com/messages/web) in NeIC slack.

### Work locally
1. Clone the source code to your laptop.
2. Serve it with `jekyll serve`.
3. See changes live on [http://localhost:4000/](http://localhost:4000/).
4. Edit until happy.
5. Commit.
6. Push your changes back to GitHub.

[Full guide here](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/).

### Show your changes to others
If you work in a fork then you can point others to YOURNAME.github.io/neic.no to show them your work
(but nothing is shown until you actually commit a change).

Example: yohell.github.io/neic.no

### What's where?
We use Jekyll collections. Information on similar things are in the same folder.
Examples:

* People are in _people/.
* Activities are in _activities/.
* News articles are in _posts/.
* ...you get the idea.

### How do I edit something?
Find something that's similar to what you want. Copy it if you need to.
Edit it until it is how you want it. Commit.

* Preferred method: Fork and pull request ([guide here](https://help.github.com/articles/fork-a-repo/))
* For very minor things like updating an email address: Edit in place.

The best way is to [work locally](#work-locally), 
then [show your changes to others](#show-your-changes-to-others).

### What if something goes wrong?
Ask in [#web](http://neic.slack.com/messages/web) in NeIC slack, but here's the
basics depending how you were working:

#### If you were working "in place"
Very quickly go ask someone in [#web](http://neic.slack.com/messages/web) in
NeIC slack if they can help you fix your mess.

#### If you were working the proper way
(eg you were working on a fork/clone, ie not "in place")

The nuclear option is always easiest: just delete the mess.
1. Make a new clone of whatever you were working on and which worked before you broke it.
2. Copy over the stuff you want and not the stuff you don't want.
3. Commit.
4. Push back your changes.
5. Delete the old mess you made.

## License
Text is licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).
Source code is licensed under [MPL v2.0](../master/LICENSE).
