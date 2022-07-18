FROM node:16

# ワーキングディレクトリを作成
WORKDIR /usr/src/app

# # Install app dependencies
# COPY package.json ./
# COPY package-lock.json ./
# RUN npm install

# ソースコードをコピー
ADD . .

USER node

# ポートを解放
EXPOSE 8080

# コマンド
CMD ["node","index.js"]