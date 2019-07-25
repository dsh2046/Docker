### Docker
1. `docker run` = `docker create + docker start` <br /><br />
2. Create image based on a Dockerfile <br />
`docker build -t web -f Dockerfile.dev .`<br /><br />
3. Based on the image 'web', start it <br />
`docker run -p 3000:3000 -v /app/node_modules -v $(pwd):/app web`


