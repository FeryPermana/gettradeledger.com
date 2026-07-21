FROM node:22-alpine

WORKDIR /app

# Copy package.json
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy sisa file
COPY . .

# Expose port Vite
EXPOSE 5173

# Jalankan server Vite
CMD ["npm", "run", "dev", "--", "--host", "0.0.0.0"]