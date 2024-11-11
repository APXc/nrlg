
# node-red-apxc-lib-node-gen alias nrlg 

tool Generator project for build Node-RED Nodes lib

 by Alessio Pellizzaro <alessio.pellizzaro@apserial.it> - Italy

 ## Generation files

 this tool generate a base structure for make a Node-RED node lib, 
the schema it's a equal of [APXC Template Nodes Library for Node-RED](https://github.com/APXc/node-red-contrib-template)

## usage

```bash
npx nrlg [projectName]
```

## example Output

```bash
🚀 node-red-apxc-lib-node-gen alias nrlg - v0.0.1
🤖 tool Generator project for build Node-RED Nodes lib

 🧑‍💻 by Alessio Pellizzaro <alessio.pellizzaro@apserial.it> - Italy

✔ Name of Project? mynodes
mynodes
✔ Yuor Name? (nametag) apxc
apxc
✔ the number of port to expose Node-Red on Your System? 1880
1880
✔ Do you have test? no
false
📁  Path Created: /mynodes/nodes/input
📁  Path Created: /mynodes/nodes/configs
📁  Path Created: /mynodes/utils
📁  Path Created: /mynodes/examples
 📝 - File Created: /mynodes/README.md
 📝 - File Created: /mynodes/.gitignore
 📝 - File Created: /mynodes/docker-compose.yml
 📝 - File Created: /mynodes/AUTHORS.txt
 📝 - File Created: /mynodes/CHANGELOG.md
 📝 - File Created: /mynodes/LICENSE
 📝 - File Created: /mynodes/package.json
 📝 - File Created: /mynodes/nodes/configs/my-configs-node.js
 📝 - File Created: /mynodes/nodes/configs/my-configs-node.html
 📝 - File Created: /mynodes/nodes/input/my-input-node.js
 📝 - File Created: /mynodes/nodes/input/my-input-node.html
 📝 - File Created: /mynodes/utils/support.js
Completed! 😄
next steps: 
 cd mynodes 
 npm install 
 docker compose up 
 npm run update 
Run make your code! 🚀
```
