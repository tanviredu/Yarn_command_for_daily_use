# Yarn and NPM Command For Basic To Advance Use

-----------------

1)  

**install the  yarn** 

​	when you install Node it will come with **npm**: as package manager .you an install the yarn with **npm**	

```bash
npm install yarn -g       [with administrative power in windows]
sudo npm install -g yarn  [in linux]
```

Now you have **npm** and **yarn** both



2)  

**Create package.json file**

**in yarn**

```bash
yarn init
yarn init -y
```

but remember you cant get scripts section in **yarn init** you need to add it manually.so i prefer **npm init** for creating **package.json**

**For npm ** 

```bash
npm init
npm init -y
```



3) 

**Install packages**

If your project have already information with the dependency then just go to the folder and type **yarn** .for example i have project in **myproj** folder with **package.json** file

[for yarn]

```bash
cd myproj
yarn
```

  or

```bash
cd myproj
yarn install
```



For **npm**  

```bash
cd myproj
npm install
```



4) 

**Adding new dependencies**

for **yarn** 

```bash
yarn add <package name>
```



for **npm** 

```bash
npm install <package name>
```



5) 

**Install dev dependencies** 

for **npm**

```bash
npm install <package> --save-dev
```

for **yarn**

```bash
yarn add <package> --dev
```

6) 

**removing packages**

for **yarn**

```bash
yarn remove <package name>
```

for **npm**

```bash
npm unistall <package name>
npm remove <package name>
```

 

7) 

**Update package**

for **npm**

```bash
npm update <package name> [for specfic package]
npm update                [for all the package]

```

for **yarn**

```bash
yarn upgrade <package name> [for specfic package]
yarn upgrade                [for all the package]
```

8)  

**run scripts**

for known command like **start**

for **yarn**

```bash
yarn start
```

for **npm**

```bash
npm start
```

**For custom command**

for **yarn** 

```bash
yarn run <command>
```

for **npm**

```bash
npm run <command>
```



9) 

**Global package install**

for **yarn**

```bash
yarn global add <package_name>
```

for **npm**

```bash
npm install <package_name> -g
```



10) 

**Get a  list of package**

in **npm [for local]**

```bash
npm list --depth=0
```

in **npm [for global]**

```bash
npm list -g --depth=0
```

in **yarn [for local]**

```bash
yarn list
```

in **yarn [for global]**

```bash
yarn global list
```



11) 

**Get Package description**

for **npm**

```bash
npm info <package_name>
```

for **yarn**

```bash
yarn info <package_name>
```



12) 

**Clean cache** 

in **npm** 

```bash
npm cache clean 
npm cache clean --force 
```

in **yarn**

```bash
yarn cache clean 
```





## Only For Yarn

1) 

**check if the version is lined up with the Repository**

```bash
yarn check
yarn check--integrity
```

2) 

**Remove unused dependencies**

```bash
yarn clean
```

3) 

**get all the licenses with github link**

```bash
yarn licenses list
```

4) 

**Upgrade dependencies interactively**

```bash
yarn upgrade --interactive
```

 