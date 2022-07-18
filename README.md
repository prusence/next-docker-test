# Clone
`git clone git@github.com:prusence/next-docker-test.git`

# Development

## イメージビルド
`docker-compose build`

## コンテナ起動
`docker-compose up`

# Production

```bash
# Build Image
docker build -f Dockerfile.prod -t nextjs-docker .

# Docker Run
docker run -p 3000:3000 nextjs-docker
```
