# 0x03. Shell, init files, variables and expansions

## Task 0: <0-alias>
Create a script that creates an alias.

- **Name:** `ls`  
- **Value:** `rm *`

### Example

```bash
julien@ubuntu:/tmp/0x03$ ls
0-alias  file1  file2
julien@ubuntu:/tmp/0x03$ source ./0-alias 
julien@ubuntu:/tmp/0x03$ ls
julien@ubuntu:/tmp/0x03$ \ls
julien@ubuntu:/tmp/0x03$ 

⚠️ Warning: This alias is destructive because running ls after sourcing the script will delete all files in the current directory. Use \ls to bypass the alias and list files normally.