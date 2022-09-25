1. 在 Offchain Worker 中，使用 Offchain Indexing 特性实现从链上向 Offchain Storage 中写入数据
    ![](./substrate-node-template/images/2.png)
    ![](./substrate-node-template/images/1.png)
2. 使用 js sdk 从浏览器 frontend 获取到前面写入 Offchain Storage 的数据
3. 回答链上随机数（如前面Kitties示例中）与链下随机数的区别

    ```
	链上生成的是伪随机数，链下生成的是真随机数
    ```