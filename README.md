# humble_devel
## How to use
```bash
git clone https://github.com/murilopauloo/humble_devel.git
cd humble_devel
```
Now you are inside the repo, for use the ROS2 humble container you need to build the image

```bash
docker compose build
```

After the build is complete you have to create the container and after that get inside it

```bash
docker compose up ros_humble -d
docker exec -it ros_humble bash
```