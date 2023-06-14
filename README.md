# blog_aula
GITZIN ATIVIDADE

Nicol@NickLee MINGW64 /c/xampp1/htdocs/blog_aula (master)
$ git clone https://github.com/nicollemelo/blog_aula-1.git
Cloning into 'blog_aula-1'...
remote: Enumerating objects: 51, done.
remote: Counting objects: 100% (51/51), done.
remote: Compressing objects: 100% (39/39), done.
remote: Total 51 (delta 8), reused 47 (delta 4), pack-reused 0
Receiving objects: 100% (51/51), 135.67 KiB | 964.00 KiB/s, done.
Resolving deltas: 100% (8/8), done.

Nicol@NickLee MINGW64 /c/xampp1/htdocs/blog_aula (master)
$ cd blog_aula
bash: cd: blog_aula: No such file or directory

Nicol@NickLee MINGW64 /c/xampp1/htdocs/blog_aula (master)
$ git add .
warning: adding embedded git repository: blog_aula-1
hint: You've added another git repository inside your current repository
hint: Clones of the outer repository will not contain the contents of
hint: the embedded repository and will not know how to obtain it.
hint: If you meant to add a submodule, use:
hint:
hint:   git submodule add <url> blog_aula-1
hint:
hint: If you added this path by mistake, you can remove it from the
hint: index with:
hint:
hint:   git rm --cached blog_aula-1
hint:
hint: See "git help submodule" for more information.

Nicol@NickLee MINGW64 /c/xampp1/htdocs/blog_aula (master)
$ git commit -m "nana do guarana"
[master 2fd9deb] nana do guarana
 1 file changed, 1 insertion(+)
 create mode 160000 blog_aula-1

Nicol@NickLee MINGW64 /c/xampp1/htdocs/blog_aula (master)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 334 bytes | 334.00 KiB/s, done.
Total 2 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/nicollemelo/blog_aula-1.git
   3901979..2fd9deb  master -> master
