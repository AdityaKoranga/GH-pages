# GH-pages
1. On one Terminal, locate to the docs ,then remove build file(if present) using this command:
```bash
sudo rm -rf build/
```

2. Then use these commands
```bash
docker-compose
sudo docker-compose up
```
3. Now on another terminal, after the completion of 1st, locate to inside of the build file i.e.
```bash
cd build/_build/html
```

4. Then finally run the command
```bash
sudo python3 -m http.server 80
```