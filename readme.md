# Ebook Library Setup
> I want to have a ebook library that stays constant across devices and to eliminate the risk of losing any data.

This was my process that I went through to find a solution.

## Storage options
Went with google drive as its convinient and has more than what I need space wise
![all storage options](1.png)

## Rsync
Ditched because the transfer speed is a roadblock
![Failed attempt with rsync](2.png)

## Rclone
Works over internet
![Success with rclone](3.png)

optional: `rclone copy ~/.local/share/com.github.johnfactotum.Foliate books-library:/Foliate-data`
to sync bookmarks, annotations, etc across devices with foliate