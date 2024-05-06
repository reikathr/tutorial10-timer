#### Nama: Athira Reika
#### NPM: 2206031422
#### Kelas: Adpro B
---
### Refleksi

#### 1.2 Understanding how it works

The println outside of the spawner.spawn() is executed before the println inside. As an async function, it runs separately as it waits for the result of a future, while the println outside of it can be executed first as main proceeds to run.

![alt text](image.png)