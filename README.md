# Docker_lab7

Wykorzystane polecenia:

sudo docker buildx build -t docker.io/lukas5555510/repolab7:lab7 --platform linux/amd64,linux/386 --push .

![image](https://user-images.githubusercontent.com/83607788/236690100-6469a23f-cc00-47d4-84b3-c3ef584bd678.png)

sudo docker run -d -p 8181:80 lukas5555510/repolab7:lab7

![image](https://user-images.githubusercontent.com/83607788/236690152-873b636d-d854-4cde-947c-c09ccb297970.png)

Manifest:

![image](https://user-images.githubusercontent.com/83607788/236690201-660d4887-b4e3-499a-8a96-dfa0c42ec731.png)

Poprawność uruchomienia serwera:

![image](https://user-images.githubusercontent.com/83607788/236690238-362259bf-735d-4908-b8c4-11d2376dad96.png)
