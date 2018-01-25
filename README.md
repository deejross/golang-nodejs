# Go + Node.js Docker Image
This project combines the Go and Node.js build environments into a single Docker image. This is useful if you are writing a web application using Go as your backend and Javascript that requires transpilation for your frontend (i.e. React, Angular, Vue.js, etc).

Your source code should go into the `/go/src` directory with the appropriate structure. If your source lives at `https://github.com/me/my-project`, you chould use a `COPY` directive in your Dockerfile to copy your source to `/go/src/github.com/me/my-project`.

Go tools provided:
* go
* dep
* glide

Node.js tools provided:
* node
* npm
