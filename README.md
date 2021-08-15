# filebrowser
I did not make this tool but it is something that I currently use often

docker pull command
docker pull filebrowser/filebrowser

docker run \
    -v /path/to/root:/srv \
    -v /path/filebrowser.db:/database.db \
    -v /path/.filebrowser.json:/.filebrowser.json \
    --user $(id -u):$(id -g)
    -p 80:80 \
    filebrowser/filebrowser
    
    please see authors page for more information
    https://filebrowser.org/installation
    https://hub.docker.com/r/filebrowser/filebrowser
    
