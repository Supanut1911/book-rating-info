# Bookinfo Application for Workshop

## step build

1. create dockerfile
2. docker cli build

    docker build -t <ชื่อimg> <ที่อยู่ dockerfile>
    
    docker build -t ratings .
    
3. docker cli run

    docker run -d --name <ชื่อ container> -p <port> <ชื่อ docker image>
  
    docker run -d --name ratingApp -p 8080:8080 ratings
  
  
