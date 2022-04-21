# Squeeth Monorepo Local deploy

1. Add the infura endpoint of Ropsten network in the docker-compose.yml file.
2. Start docker with `sudo docker-compose up` going to the docker-compose folder.
3. Navigate to the Subgraph folder by typing `cd packages/subgraph`
4. Install Yarn by running `yarn install`
5. Rename the 'subgraph.template.yaml' file to 'subgraph.yaml' in the "Subgraph" package.
6. Navigate to Squeeth>packages>services>graph-node. Open terminal there and type `sudo docker-compose up` to start docker.
7. 

#Run in frontend
1. Create a new file called `.env.local` and copy the contents of "env.example"
2. Add Infura API key and Blocknative API key 
3. Go to "package.json" in frontend and run `yarn install`
4. Run `yarn dev`
5. Go to localhost:3000
