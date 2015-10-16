# Tech Skills Bootcamp

## Before you start

If you do not have access to a linux system, we strongly recommend using [Vagrant](https://www.vagrantup.com/) in conjunction with [VirtualBox](https://www.virtualbox.org/). 

Note that if you're on Ubuntu Linux already and you want to try this Vagrant thing out, you're going to want to get the on from the website and not the one from ``apt-get``, as it is [out of date and not compatible with most images](https://github.com/fideloper/Vaprobash/issues/322).

## Fork this repository!

Fork this repository, and clone your copy once you're inside vagrant.

    https://github.com/${GITHUB_USER_NAME}/tech-skills-bootcamp.git 
    cd tech-skills-bootcamp

## Add your username to the participants file!

Open the file for editing with ``nano``. If you're familiar with ``vim`` or ``emacs`` we've installed those for you, too. ``nano`` is very simple to use, though.

Add your CS or github username to the file; go ahead and make one up if you don't have one -- and don't delete anyone elses! Feel free to also record the date!

    nano participants.md

Tell ``git``, the version control system that you've changed the file:

    git add participants.md

Now tell ``git`` you're done changing things for now, and push your changes up to your fork of the repository.

    git commit # save changes locally
    git push # send them up to the server


