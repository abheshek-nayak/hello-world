

## :point_right: Demonstrate minimum 15 basic docker command with explanation and screenshot.


	1. Docker pull <image> --> It pulls the image from Docker Repository 
  ![image](https://user-images.githubusercontent.com/86867435/196718087-4a299ce4-4d4b-484c-af1e-3edfadfbb729.png)

	

	2. Docker run <image> - > Run the Docker Image
 ![image](https://user-images.githubusercontent.com/86867435/196718187-db0de28b-737f-483e-b227-6f6713535e95.png)



	3. Running an image in detached mode
	Docker run -d <image>

![image](https://user-images.githubusercontent.com/86867435/196718272-25d5dce7-7ed5-4054-afff-a1ec91f7c078.png)


	4. Docker attach - attach to a running container
	Docker attach <Container I.D>
![image](https://user-images.githubusercontent.com/86867435/196718493-1196f689-25fe-461c-95c9-4a131b1c3058.png)


Note: Simply provide the first few characters of the CONTAINER I.D

	5. Pause and Unpause a Container
![image](https://user-images.githubusercontent.com/86867435/196718656-7bd1e790-6137-4545-a99a-3f8cd11998a5.png)



	6. Docker ps -> It lists all running containers and  basic information about them
  ![image](https://user-images.githubusercontent.com/86867435/196718808-253dedb3-e3c8-45bb-a69a-9036cba88342.png)



	7. Docker ps -a --> To see the list of all containers including running and exited ones 
![image](https://user-images.githubusercontent.com/86867435/196718913-c7d99db2-9fae-4202-bded-502bc8d7e35e.png)




	8. Docker stop -> 
	To stop a running container use the Dockers stop command but you must provide either the container I.D. or the container name.

![image](https://user-images.githubusercontent.com/86867435/196719082-ac8f9127-4a9b-4859-9ed4-53f676ee13a7.png)



	9. Remove a Container
	To remove a container - > docker rm <container name>
![image](https://user-images.githubusercontent.com/86867435/196719116-7d724e0c-bd74-4cbf-877e-d7b5b1d7beab.png)



	10. To see a list of images
![image](https://user-images.githubusercontent.com/86867435/196719147-58e12f2e-978d-4776-9341-bd99294eafd3.png)



	11. Removing an image

DOCKER rmi <image name>
![image](https://user-images.githubusercontent.com/86867435/196719184-d8f65348-fbd6-4819-beb5-b7e68aa03c8a.png)




	12. History of image -> show the history of the particular image
![image](https://user-images.githubusercontent.com/86867435/196719546-be192f62-1def-4c9c-a4b7-2281dfd1c6d2.png)



	13. Inspect an image - shows the low level information in JSON format

![image](https://user-images.githubusercontent.com/86867435/196719272-6d3ea601-331d-40b0-92ea-0cb57e5a6a67.png)



	14. Creating an image
![image](https://user-images.githubusercontent.com/86867435/196719307-4beac02a-0ed5-454c-ab28-ca10a5761f28.png)




	15. Renaming a container

Docker rename <old-name> <new-name>
![image](https://user-images.githubusercontent.com/86867435/196719344-55b7ddc9-6631-4e92-bdc1-df35b26c13aa.png)




