# agnoster-fcamblor.zsh-theme

A ZSH theme optimized for people who use:

- Solarized
- Git
- Unicode-compatible fonts and terminals (I use iTerm2 + Menlo)

For Mac users, I highly recommend iTerm 2 + Solarized Dark

# Install
- Run ``install`` script to copy theme to your ~/.oh-my-zsh folder

# Compatibility

**NOTE:** In all likelihood, you will need to install a [Powerline-patched font](https://github.com/Lokaltog/powerline-fonts) for this theme to render correctly.

To test if your terminal and font support it, check that all the necessary characters are supported by copying the following command to your terminal: `echo "⮀ ± ⭠ ➦ ✔ ✘ ⚡"`. The result should look like this:

![Character Example](http://cl.ly/content/image/2l3w443z363P/aHR0cDovL2YuY2wubHkvaXRlbXMvM2ozTjJpMDMzTzJNM0ozcDFjMjgvU2NyZWVuJTIwU2hvdCUyMDIwMTItMDktMTQlMjBhdCUyMDEyLjA2LjAyJTIwLnBuZw==)

## What does it show?

- If the previous command failed (✘)
- User @ Hostname (if user is not DEFAULT_USER, which can then be set in your profile)
- Working directory
- Git statuses
  - Dirty working directory (orange / green)
  - Branch (⭠) or detached head (➦)
  - Current branch / SHA1 in detached head state
  - Remote branch name (if you're tracking a remote branch)
  - Number of commit ahead HEAD and behind remote tracking branch (remote tracking segment will be magenta if merge/rebase is needed)

![Screenshot](https://gist.githubusercontent.com/fcamblor/f8e824caa28f8bea5572/raw/8c96ec7d669edac8ae1e1935fe389ee7b3bf543c/screenshot.png)
