<h1 align="center">
    Integration shared librabry in Pipline
</h1>




<p>1. Go to Dahsboard ->  Manage Jenkins -> Configuration System -> Global Pipeline Libraries</p>


![Screenshot 2023-04-03 at 10 02 01](https://user-images.githubusercontent.com/69374541/229401775-c2530695-bbba-41ef-8ea3-9b5f02583cd9.png)


<p>2. How to implement this library by Vars directory </p>

`@Library('shared-library-jenkins') _`
  
![Screenshot 2023-04-03 at 10 04 05](https://user-images.githubusercontent.com/69374541/229401995-45730e00-c35a-4bda-a2ca-edf5a847eebd.png)


<p>3. How to implement this library by src directory </p>

`import classschema.jenkins.Output`

![Screenshot 2023-04-03 at 10 04 05](https://user-images.githubusercontent.com/69374541/229401995-45730e00-c35a-4bda-a2ca-edf5a847eebd.png)

Reference where i learned this: https://youtu.be/RZqdjlP4gSc
