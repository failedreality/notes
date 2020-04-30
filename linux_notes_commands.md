cat

chmod
    chmod <file> perms
    3 digit number that controls specific perms
    User|Group|Everyone else not a user/group
    777 = All perms to everything

    Perms range from 1-7 with 1 the most restrictive

    Also learned about the perms before the file info on a ls -al
    10 digits
        ignore the first - after the first is USER | Group | Everyone Else
        -rw-r--r-- 
        rw- = User
        r-- = Group
        r-- = Everyone else
        So listed above the effective perms would be 644

rm = remove         
mv - move           mv <file> <dest>
mkdir - make dir    mkdir <name>
cp = copies         cp <file> <dest>
cd = change dir
ln = hard linking   ln <source> <dest>
ln -s = symlink     ln -s <file> <dest> ** Reference pointer **


find && grep
    I'm still struggling with this one, so more notes will come
    
    grep <string> <file1> <file2>

