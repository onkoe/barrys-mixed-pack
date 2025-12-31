# README

Assistance for setting up the server.

## Setup

Extract this archive (the one that contains this very `README` file) to your server. Then, to set up the Minecraft server, follow these instructions:

- Download [the Forge installer](https://maven.minecraftforge.net/net/minecraftforge/forge/1.12.2-14.23.5.2864/forge-1.12.2-14.23.5.2864-installer.jar) onto your personal computer, then type `java -jar forge-1.12.2-14.23.5.2864-installer.jar`, then use the GUI that pops up to download the server JAR.
- Upload that resulting `forge-1.12.2-14.23.5.2864.jar` onto your server
- Ensure your server has Java 8 installed, and alias it to `java8` (e.g., in `.bashrc`).
- Accept the EULA via `eula.txt`.
- Edit `launch.sh` to have the right amount of maximum memory (current is 6 GiB), then make the script runnable: `chmod +x launch.sh`
- Launch the server: `./launch.sh`

## Running

After you do that setup above, you can run it via this command: `./launch.sh`.

Make sure to take frequent backups to avoid losing your worlds, and please [report any bugs](https://github.com/onkoe/barrys-mixed-pack/issues/new) you find! :)
