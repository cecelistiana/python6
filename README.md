# python6
1. Exception

source code

try:

    level = input ("level kartu : ")
    
    level = int (level)
    
    level = level / 0
    
    print(level)
    
except ZeroDivisionError:

    print("error tidak bisa dibagi dengan 0")
    
except ValueError:

    print("yang kamu masukan itu bukan angka")
    
vc code dan output
![p31](https://user-images.githubusercontent.com/92987122/141305294-1863bf1d-b9af-45c2-b460-17a5bba715fe.png)

2. General Exception

source code

try:

    level = input ("level kartu : ")
    
    level = int (level)
    
    level = level / 0
    
    print(level)
    
except:

    print("terjadi kesalahan")
    
vc code dan output
![p32](https://user-images.githubusercontent.com/92987122/141305443-38243ef1-70b7-45ce-b05d-c6b9c57da1d6.png)

3. Menulis File

source code

users = open("users.txt")

print(users.read())

users.close()

vc code dan output
![p33](https://user-images.githubusercontent.com/92987122/141305541-a4d85ced-6313-4bea-9dcd-c3c6745850de.png)

4. Membaca File

source code

users = open("users.txt", "a")

users.write("zdfghj")

users.close()

vc code dan output
![p34](https://user-images.githubusercontent.com/92987122/141305635-a7f9e6b4-f497-431d-be8e-a444977731c8.png)
![p35](https://user-images.githubusercontent.com/92987122/141305656-af522e93-b9ff-43dc-9d4c-a6b506c9ac7e.png)

