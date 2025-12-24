# 平安夜快乐网页 🎄

## 文件说明
- `index.html` - 网页文件
- `avatar.jpg` - 小狗头像（需要你自己添加）

## 部署方法（免费）

### 方法一：Vercel（推荐，最简单）
1. 访问 https://vercel.com
2. 用 GitHub/Google 账号登录
3. 点击 "Add New..." → "Project"
4. 选择 "Import Git Repository" 或直接拖拽文件夹上传
5. 点击 "Deploy"
6. 完成！会给你一个 `xxx.vercel.app` 的链接

### 方法二：Netlify（也很简单）
1. 访问 https://app.netlify.com/drop
2. 直接把 `christmas_eve` 文件夹拖拽到页面上
3. 等几秒钟就部署好了
4. 会给你一个随机链接，可以自定义

### 方法三：GitHub Pages
1. 创建 GitHub 仓库
2. 上传文件
3. Settings → Pages → 选择分支 → Save
4. 等待几分钟即可访问

### 方法四：Surge.sh（命令行）
```bash
npm install -g surge
cd christmas_eve
surge
```
按提示操作，输入邮箱即可，会给你一个 `xxx.surge.sh` 链接

## 预览
本地预览：
```bash
cd christmas_eve
python3 -m http.server 8000
```
然后访问 http://localhost:8000

