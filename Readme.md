## Usage

To build and run, just do 

```bash
curl -o docker-compose.yml https://raw.githubusercontent.com/VCityTeam/TunNetDemo/master/docker-compose.yml
docker-compose build
docker-compose up
```
You can skip the `docker-compose build` command.

The results : 
- point cloud in xyz format
- 3dtiles

will appear in a newly created **results** directory

**Warning** Because rights can be granted to root for the created directory, you may need to create the **results** directory before running the up command.
