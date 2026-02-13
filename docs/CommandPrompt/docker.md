# Docker

## Docker Build
|Command|Description|
|----|----|
|docker build -t <image_name> .| Build a Docker image from a Dockerfile in the current directory and tag it with a name.|
|docker build --no-cache -t <image_name> .|Build a Docker image without using the cache.|
|docker build -f <dockerfile_name> -t <image_name> .|Build a Docker image using a specified Dockerfile.|

## Docker Clean Up
|Command|Description|
|----|----|

## Container Inspection
|Command|Description|
|----|----|
|docker ps|List running containers.|
|docker ps -a|List all containers, including stopped ones.|
|docker logs <container_id>|Fetch the logs of a specific container.|
|docker inspect <container_id>|Inspect detailed information about a container.|

## Reference
1. [Docker Cheat Sheet](https://www.coursera.org/collections/docker-cheat-sheet?utm_medium=sem&utm_source=gg&utm_campaign=b2c_apac_x_multi_ftcof_career-academy_cx_dr_bau_gg_pmax_pr_s3_en_m_hyb_25-04_desktop&campaignid=22420706570&adgroupid=&device=c&keyword=&matchtype=&network=x&devicemodel=&creativeid=&assetgroupid=6566444276&targetid=&extensionid=&placement=&gad_source=1&gad_campaignid=22424263906&gbraid=0AAAAADdKX6bm83dJbqTdSr2RXmmm1Y6xv&gclid=EAIaIQobChMI68Kiy-nVkgMVOyeDAx2P_RzyEAAYAiAAEgKh1vD_BwE)