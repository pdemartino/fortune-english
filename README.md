# fortune-english
Just a stupid fortune recipe to help me brushing up on my english skills.
I'm a programmer, if I learnt a new english word each time I used my shell at this time I would be Shakespeare.
Install this fortune recipe and every time you'll open your bash it will teach something new to you.

This recipe contains:
* Irregular verbs


## How to install

### Step 0 - Install GNU fortune
In order to get your daily english cookie you have first to install fortune.

#### Install in Debian (and Debian's derivates)
```
sudo apt-get install fortune-mod
```

#### Install in Mac OS
 * Install [Homebrew](http://brew.sh/)
 * Install fortune:
 ```
 brew install fortune
 ```

### Step 1 - Clone this repository
```
FE_HOME=$HOME/github/fortune-english # Use the path you prefer
git clone git@github.com:pdemartino/fortune-english.git $FE_HOME
```

### Step 2 - Modify your .bashrc
Append the following lines to your $HOME/.bashrc:
```
# fortune-english: git@github.com:pdemartino/fortune-english.git
FE_HOME=$HOME/github/fortune-english # Use the same path as before
echo 'Your daily english cookie'
fortune $FE_HOME
```

## How to use
Just run your bash!


## How to remove
If you've become an english master, maybe it's now time to remove fortune-english; just follow the installation steps in reverse order and you'll get rid of it.
