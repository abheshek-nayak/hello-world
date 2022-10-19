## Automate Assignment below task using github action.

    Build Docker Image
    Push Docker Image to Docker hub.
    
   ***Step 1 : Push your project files into the GitHub repository(must include the Dockerfile)***

   ***Step 2: In your Repository***

  :octocat: Settings --> Secrets --> Actions--> New Repository Secret

   Create and save a password
   
![image](https://user-images.githubusercontent.com/86867435/196723116-8e4a6bbe-b2c8-4600-9442-0dc0c130682f.png)

***Step 3:  Go to Actions --> New workflow--> Click on Docker Image  Configure***
![image](https://user-images.githubusercontent.com/86867435/196723259-862a8aad-5729-475d-89b7-958f68f649e7.png)

***A default YAML template props up***
![image](https://user-images.githubusercontent.com/86867435/196727017-b6c0b8ac-a13a-470f-bf3a-4dd3878597c9.png)

***Step 4: 
In the Steps -> run(highlighted above in red box) ,provide these three things:-***

	• Line 1 - Docker Password and Login credentials
	• Line 2 - Docker build image command
	• Line 3 - Docker push the image to repository 
![image](https://user-images.githubusercontent.com/86867435/196723462-463123a9-06e9-4576-9bea-504842b45a2e.png)

***Step 5: Commit the file***

After image is build and uploaded to the Docker repository,check it in Docker Hub
![image](https://user-images.githubusercontent.com/86867435/196723585-acec1068-2455-475e-a49e-a58f9cfcdd75.png)

**Test :-**

``` docker pull abhishekc2q/hello-world2``` <br>
``` docker run -d --name mycontainer -p 80:80 abhishekc2q/hello-world2``` <br>

> In the Browser - http://127.0.0.1/docs




