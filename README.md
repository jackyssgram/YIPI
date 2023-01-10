給LEO大大

App.js裡面請加入

[1] import  NewsId

[2] <Route path="/news/newsId" element={<NewsId />} />

containers/index.js

[1]export { default as NewsId } from './news/NewsId';

containers/news/News.jsx
[1]  <button>
      <Link to="NewsId">展覽活動</Link>
    </button>
