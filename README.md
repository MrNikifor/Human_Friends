### Задание 1

cat > "Pets animals" <<EOF
Dogs
Cats
Hamsters
EOF

cat > "Pack animals" <<EOF
Horses
Camels
Donkeys
EOF

cat "Pets animals" "Pack animals" > "Animals"
cat "Animals"
mv "Animals" "Human Friends"
cat "Human Friends"

![Задание 1.png](..%2F..%2FUsers%2Fosian%2FOneDrive%2FPictures%2FScreenshots%2F%C7%E0%E4%E0%ED%E8%E5%201.png)

### Задание 2

mkdir Animals
mv 'Human Friends' Animals/
cd 'Human Friends'
cat 'Human Friends'
cd Animals
cat 'Human Friends'

![Задание 2.png](..%2F..%2FUsers%2Fosian%2FOneDrive%2FPictures%2FScreenshots%2F%C7%E0%E4%E0%ED%E8%E5%202.png)

### Задание 3

sudo wget https://dev.mysql.com/get/mysql-apt-config_0.8.23-1_all.deb

sudo dpkg -i mysql-apt-config_0.8.23-1_all.deb
sudo apt-get update
sudo apt-get install mysql-server

![Задание 3.png](..%2F..%2FUsers%2Fosian%2FOneDrive%2FPictures%2FScreenshots%2F%C7%E0%E4%E0%ED%E8%E5%203.png)

![Задание 3.1.png](..%2F..%2FUsers%2Fosian%2FOneDrive%2FPictures%2FScreenshots%2F%C7%E0%E4%E0%ED%E8%E5%203.1.png)

![Задание 3.2.png](..%2F..%2FUsers%2Fosian%2FOneDrive%2FPictures%2FScreenshots%2F%C7%E0%E4%E0%ED%E8%E5%203.2.png)

![Задание 3.3.png](..%2F..%2FUsers%2Fosian%2FOneDrive%2FPictures%2FScreenshots%2F%C7%E0%E4%E0%ED%E8%E5%203.3.png)

### Задание 4

sudo apt update
sudo install nginx
sudo stop nginx
sudo apt remove --purge nginx

![Задание 4.png](..%2F..%2FUsers%2Fosian%2FOneDrive%2FPictures%2FScreenshots%2F%C7%E0%E4%E0%ED%E8%E5%204.png)