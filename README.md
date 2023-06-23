# Docker-installation

# Install and run Docker Desktop on Mac

### Links:

- Intel Mac :
```
https://desktop.docker.com/mac/main/amd64/Docker.dmg?utm_source=docker&utm_medium=webreferral&utm_campaign=dd-smartbutton&utm_location=module&_gl=1*1t9hbq1*_ga*ODE0MDcyNjczLjE2NzM4OTEzODM.*_ga_XJWPQMJYHQ*MTY4NzUwOTA1MS4yMy4xLjE2ODc1MDkzNzguNTkuMC4w
```

- M1 Chip Mac :
```
https://desktop.docker.com/mac/main/arm64/Docker.dmg?utm_source=docker&utm_medium=webreferral&utm_campaign=dd-smartbutton&utm_location=module&_gl=1*1z0bnme*_ga*ODE0MDcyNjczLjE2NzM4OTEzODM.*_ga_XJWPQMJYHQ*MTY4NzUwOTA1MS4yMy4xLjE2ODc1MDkzNzguNTkuMC4w
```

# Install and run Docker Desktop on Windows :

### Links:

- Windows :
```
https://desktop.docker.com/win/main/amd64/Docker%20Desktop%20Installer.exe?utm_source=docker&utm_medium=webreferral&utm_campaign=dd-smartbutton&utm_location=module&_gl=1*178flho*_ga*ODE0MDcyNjczLjE2NzM4OTEzODM.*_ga_XJWPQMJYHQ*MTY4NzUwOTA1MS4yMy4xLjE2ODc1MDkzNzguNTkuMC4w
```

# Install and run Docker Desktop on Linux :

- Linux :
```
https://docs.docker.com/desktop/linux/install/?_gl=1*1hyoq9c*_ga*ODE0MDcyNjczLjE2NzM4OTEzODM.*_ga_XJWPQMJYHQ*MTY4NzUwOTA1MS4yMy4xLjE2ODc1MDkzNzguNTkuMC4w
```

# Optional : 

- Create a account in `hub.docker.com` .
- So you create the docker images in local and store it in DockerHub .
- They provide unlimited storage and public repos .
- Only 2 private repos can created in free version .


# Overview :

- When you open Docker Desktop, the Docker Dashboard displays.

<img width="1381" alt="image" src="https://github.com/Kamalesh-Seervi/Docker-installation/assets/107933310/4ec5e16d-747d-49a8-81b1-12769768a113">

- The **Containers** view offers a real-time display of your containers and applications, providing you with the ability to engage with them and oversee their lifecycle directly from your device. This view presents a user-friendly interface that enables you to easily perform various tasks such as examining, interacting with, and overseeing your Docker objects, encompassing containers and applications built with Docker Compose.

- The **Images** view presents a comprehensive listing of your Docker images, providing functionalities such as running an image as a container, retrieving the most recent version of an image from Docker Hub, and inspecting images. It also offers a concise overview of image vulnerabilities. Moreover, within the Images view, you can conveniently utilize cleanup options to eliminate unnecessary images from your disk, allowing you to free up storage space.

- The **Volumes** view displays a list of volumes and allows you to easily create and delete volumes and see which ones are being used.


# Now lets Run our tms docker :

- **Step-1 :** Get access to the repo .
- **Step-2 :** After pulling the code in Vscode .
- **Step-3 :** Go to terminal and type docker compose up .

<img width="1136" alt="image" src="https://github.com/Kamalesh-Seervi/Docker-installation/assets/107933310/c29fcad2-6a5b-4ad2-abea-11a15d734dcc">

- **Step-4 :** You can that check that the simulator is running successfully in `localhost:3000`.
- **Step-5 :** You can modify code in the tms directory it will be automactically changed in docker container because i have used Bind mount .

 ![image](https://github.com/Kamalesh-Seervi/Docker-installation/assets/107933310/bfc76203-9beb-4406-ac7f-f47385f998e6)



# Note :

- If you get issues like `The Docker daemon isn't running on your system'.

<img width="1136" alt="image" src="https://github.com/Kamalesh-Seervi/Docker-installation/assets/107933310/40ff640d-a76c-45f3-8158-dca538c4c1e4">

- This error is because docker desktop is not running .
- Run the docker .




