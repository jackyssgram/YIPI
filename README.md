給LEO大大
這是


![image](https://user-images.githubusercontent.com/117629733/211531521-76c4373b-041f-44a2-bdcc-fa3f4f987c66.png)


App.js裡面請加入

[1] import  NewsId

[2] <Route path="/news/newsId" element={<NewsId />} />

containers/index.js

[1]export { default as NewsId } from './news/NewsId';

containers/news/News.jsx
[1]  <button>
      <Link to="NewsId">展覽活動</Link>
    </button>
RWD也已完成
