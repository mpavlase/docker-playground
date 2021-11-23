# 1. vytvořit image z nginx, tag si zvol podle sebe s odůvodněním
FROM nginx:alpine

# 2. nakopíruj default.conf do /etc/nginx/conf.d/default.conf
COPY default.conf /etc/nginx/conf.d/default.conf

# 3. build image
# 4. vytvoř síť typu bridge s názvem 'mydockernetwork'
# 5. spusť image, vystav port 80 ven, container má být na síti 'mydockernetwork'
