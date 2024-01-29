# Example Repository
This is a sample repo, Hello world!

Git Cheatsheet
https://github.com/joshnh/Git-Commands

How to connect with GIT: https://www.youtube.com/watch?v=Wqgw-v9OVGI
- Run, ls -al ~/.ssh in bash
- Created .ssh folder inside Admin page
- Right click inside folder and "Open git bush here"
- Type ssh-keygen -t rsa -b 4096 -c "gauravt3091@gmail.com"
- Output:
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/ADMIN/.ssh/id_rsa)-
- Give the smae file name "id_rsa" (Givr password if required)
- This will create two files inside new folder
- Then type "eval $(ssh-agent -s)"
- Output:
Agent pid <key>
- Type "ssh-add id_rsa"
Identity added: id_rsa (gauravt3091@gmail.com)
- Copy and paste the public key into Github SSH and GPG keys, Add SSH keys
- Add global user
git config --global user.name "GauravLearner"
git config --global user.email "gauravt3091@gmail.com"
- To verify git configration setup properly "git config --list"
- To check SSH confrigration "ssh -T git@github.com"
- Connect to repository
1. Clone if its not available into local already
2. Otherwise, Right click inside folder and "Open git bush here"
3. Type "git status" to see changes
4. "git add ." to add into staging area
5. "git commit -m "text"" to add commit message
6. "git push origin main" to push file into git. 'main' is branch name
7. 