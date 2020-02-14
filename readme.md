# Steps

## Step 1 -> Install docker
```
sudo curl -fsSL https://get.docker.com | bash
```

```

## Step 2 -> Install docker-compose

```
sudo curl -L "https://github.com/docker/compose/releases/download/1.24.1/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
```
```
sudo chmod +x /usr/local/bin/docker-compose
```

## Step 3 -> Build Spigot
```
docker-compose -f ./run/build_spigot.yml up
```

## Step 4 -> Start Spigot
```
docker-compose -f ./run_spigot.yml up -d
```
