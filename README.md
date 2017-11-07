# Technical Support @ Planet

This is the repository of the Technical Support team at Planet. It contains all scripts and tools developed by the team both for external (customers) and internal (planeteers) support.

## Getting Started


These instructions will get you a copy of the project up and running on your local machine for development.

### Prerequisites

####SSH Keys:

* If you don't have a SHH key pair, create one running the following command in a new terminal:

```
cd ~
mkdir .ssh/save
mv .ssh/id_* .ssh/save/
ssh-keygen -t rsa -b 4096
```
This will move any previously existing keys to a the folder .ssh/save/ just in case. Take the default options and enter a passfrase when asked.

* If you do have a key or after creating one, retrieve it key by running:
```
cat ~/.ssh/id_rsa.pub
```

####Planet Github account:

* Go to [GitHub](https://github.com/) and create your own account using your Planet email address (you can use any username you want).
* Update your profile at [https://hello.planet.com/update](https://hello.planet.com/update) with the contents of your new SSH key and your github username.
* Update your profile at [GitHub](https://github.com/) with your SSH key.
* Within one hours, you should receive an invitation to Planet Labs GitHub account by email. Click the link on the email to accept the invitation.
* If the email does not arrive withing 24 hours, file a ticket at [CorpEng](https://go.planet.com/help).

### Installing

--- then clone the repo

git clone --repository address

A step by step series of examples that tell you have to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the scripts
This are instruction on what you will need to run our scripts.

### For Python

```
pip install planet
```

### For PHP

### For SQL

### For R


## Authors

* [Grischa Großmann](mailto:grischa.grossmann@planet.com)
* [Shashank Kaushik](mailto:shashank@planet.com)
* [Pooja Pandey](mailto:pooja.pandey@planet.com)
* [Luis Peraza](mailto:luis.peraza@planet.com)


