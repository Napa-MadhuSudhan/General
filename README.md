# General

## Installing Home Brew
### Step 1: Open Terminal and run the below command
``` /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)" ```
### Step 2: Run these three commands one by one 
```echo '# Set PATH, MANPATH, etc., for Homebrew.' >> /Users/<<user-name>>/.zprofile```

```echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> /Users/<<user-name>>/.zprofile```

```eval "$(/opt/homebrew/bin/brew shellenv)"```
### Step 3: Verify it by running any brew command 
``` brew update```
