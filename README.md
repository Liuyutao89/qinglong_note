
安装青龙的一些依赖


docker exec -it qinglong bash -c "npm install -g typescript"

docker exec -it qinglong bash -c "npm install axios date-fns"

docker exec -it qinglong bash -c "npm install crypto -g"

docker exec -it qinglong bash -c "npm install png-js"

docker exec -it qinglong bash -c "npm install -g npm"

docker exec -it qinglong bash -c "pnpm i png-js"

docker exec -it qinglong bash -c "pip3 install requests"

docker exec -it qinglong bash -c "apk add --no-cache build-base g++ cairo-dev pango-dev giflib-dev && cd scripts && npm install canvas --build-from-source"

docker exec -it qinglong bash -c "apk add python3 zlib-dev gcc jpeg-dev python3-dev musl-dev freetype-dev"

docker exec -it qinglong bash -c "cd /ql/scripts/ && apk add --no-cache build-base g++ cairo-dev pango-dev giflib-dev && npm i && npm i -S ts-node typescript @types/node date-fns axios png-js canvas --build-from-source"
