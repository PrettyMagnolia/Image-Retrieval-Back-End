# 2023年用户交互技术 实验二图像检索 后端

完整文件地址：http://shenyingtongji.gitee.io/home/course/HCI2023Spring/index.html

run server/image_vectorizer.py

- Run image vectorizer which passes each data through an inception-v3 model and collects the bottleneck layer vectors and stores in disc. Edit dataset paths accordingly inside the image_vectorizer.py
- This will generate two files namely, image_list.pickle and saved_features.txt. Keep them inside lib folder where search.py script is available.

 run server/rest-server.py

- Start the server by running rest-server.py. This project uses flask based REST implementation for UI

Once the server starts up, access the url (for example) 0.0.0.1:5000 to get the UI. Now upload any file and see 9 similar images. You can change the value of K from 9 to any values, but don’t forget to update the html file accordingly for displaying.



 