#lab14
Web-server with Axum and nginx proxy


# Clone project
git clone https://github.com/NewBuy60/lab14

# Install Docker
sudo pacman -S docker
sudo pacman -S docker-compose

# Install Nginx
sudo pacman -S nginx

# Launch
sudo docker-compose build
sudo docker-compose up -d

# Test
curl http://localhost/v1/todos/63443a02-2137-48e8-8db5-79fa54e8bfdf
