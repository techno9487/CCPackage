#CCPackage, Computercraft package manager

`Usage: pkg <sub-command> <args...>`
For refernce i have included the src for the example test package

**The current features are:**
- `add <name> <address>` adds a repo with name and address to the package list
- `search <query>` searches all repos in repo list for the package containing the string `query`
- `remove-repo <name>` removes repo with name `name`
- `install <package>` install a package with name `package`
- `create <folder>` creates a package from the specified folder
- `decomp <package>` decomporeses the named package to the tmp dir

**Troubleshooting**

If you consistantly get and error printing to the console then it's probably because the package list file doesn't contain any repos, if this does ahppen to you please run the following command:
`pkg add main https://raw.githubusercontent.com/techno9487/CCPackage/master/repo/manifest`
