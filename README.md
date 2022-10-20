# CAB303 testing area

Just some containers to run example attacks quickly and capture network traffic.
Dump attacks you want as .sh files in the `attacks` directory and run them with `./start.bat <attack.sh>`.
If you want more attackers just add more containers to the `docker-compose.yml` file - poor mans kubernetes.

## Usage

```bash
./start.bat <attack.sh>
```