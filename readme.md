<p><a target="_blank" href="https://app.eraser.io/workspace/DhP1ooQBW592bkevNT9e" id="edit-in-eraser-github-link"><img alt="Edit in Eraser" src="https://firebasestorage.googleapis.com/v0/b/second-petal-295822.appspot.com/o/images%2Fgithub%2FOpen%20in%20Eraser.svg?alt=media&amp;token=968381c8-a7e7-472a-8ed6-4a6626da5501"></a></p>

# Django + Docker = [﻿❤️](https://emojipedia.org/red-heart) 
Welcome to the Docker and Django tutorial - where we build a production-ready Django project with Docker.

### Setup:
You can build this project with the following command:

```
docker build -t django-docker-project:latest .
```
You can run this image with the following command:

```
docker run -p 8000:8080 \
--env PIPELINE=production \
--env SECRET_KEY=your_value \
--env DB_NAME=. \
--env DB_USER_NM=. \
--env DB_USER_PW=. \
--env DB_IP=0.0.0.0 \
--env DB_PORT=5432 \
django-docker-project
```
### Diagram:
![image.png](/.eraser/DhP1ooQBW592bkevNT9e___2z0eW5g8k6Ul26CqFFCWf88cv422___SNJl90dssWW6QVFqLyllI.png "image.png")

### Next Steps:
Connect Django to PostgreSQL (with AWS RDS)

Complete Django production class (coming soon...)


<!--- Eraser file: https://app.eraser.io/workspace/DhP1ooQBW592bkevNT9e --->