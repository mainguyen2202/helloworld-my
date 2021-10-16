# shop-laptop

# Deploy react app trên Firebase Hosting

Hướng dẫn cho người mới bắt đầu sau đây MaiNguyen chia sẻ 1 vài từ khóa(keyword) để các bạn tìm kiếm như sau:
- visual studio code : nơi viết code
- html5
- css
- bootstrap 4
- javascript
- nodejs
- npm : node_modules, init, install, update, uninstall [link](https://viblo.asia/p/npm-yarn-va-javascript-Eb85orNml2G)
- yarn: node_modules, inti, add, upgrade, remove [link](https://viblo.asia/p/npm-yarn-va-javascript-Eb85orNml2G)
- reactjs [link](https://hocwebchuan.com/tutorial/reactjs/)
- Firebase Hosting [link](https://console.firebase.google.com/u/0/)
- git : cách lệnh cơ bả clone, commit, add, pull, push, remote, .... [link](https://jobs.hybrid-technologies.vn/blog/nhung-lenh-git-co-ban-can-nho/)
- github : nơi chứa code [link](https://github.com)

## TÀI LIỆU THAM KHẢO

[1 - Reactjs : Deploy react app trên Firebase Hosting hoàn toàn miễn phí](https://viblo.asia/p/reactjs-deploy-react-app-tren-firebase-hosting-hoan-toan-mien-phi-Az45bYzglxY)

[0 - HTML5   : Deploy Website Tĩnh trên Firebase Hosting hoàn toàn miễn phí](https://www.thanhlongdev.com/huong-dan-deploy-project-website-tinh-len-firebase/)

[Link Backup - Tạo website với Firebase Hosting](https://topdev.vn/blog/tao-website-voi-firebase-hosting/)

[Bài 21: ReactJS - Tạo ứng dụng reatjs từ bootstrap 4 - Học ReactJS Full Đầy Đủ Nhất trong 21 bài](https://vncoder.vn/bai-hoc/reactjs-tao-ung-dung-reatjs-tu-bootstrap-4-317)

[Set custom domain free cho Firebase hosting](https://kipalog.com/posts/Set-custom-domain-free-cho-Firebase-hosting)

[Link Backup - Đặt tên miền tùy chỉnh miễn phí cho lưu trữ Firebase](https://itzone.com.vn/vi/article/set-custom-domain-free-cho-firebase-hosting/)

Chú ý: Một số trường hợp có thể https sẽ bị chéo đỏ fix --> Xem ở cuối link hướng dẫn

Nếu chưa có tên miền thì lên Freenom tạo [Freenom](https://www.freenom.com/en/index.html?lang=en)

[sslforfree](https://manage.sslforfree.com/certificates) tạo chứng chỉ ssl free

[startbootstrap](https://startbootstrap.com/themes/portfolio-resume?showPro=false) có những trang mẫu có css mẫu tích hợp cả thư viện bootstrap -> download về và sử dụng

Đang sử dụng template [Resume](https://startbootstrap.com/theme/resume) để làm CV ;)

[Hướng dẫn tạo tk github đẩy code lên Github](https://techmaster.vn/posts/35408/huong-dan-day-code-len-github)

[Hướng Dẫn Sử Dụng Git Và Cách Push Project Lên Kho Lưu Trữ Của GitHub](https://www.thanhlongdev.com/huong-dan-su-dung-git-va-cach-push-project-len-github/)

[Cách lưu trữ app React với Github miễn phí](https://hocweb.vn/cach-luu-tru-app-react-voi-github-mien-phi/)

Chú ý:

[Cloud Resource Manager](https://console.cloud.google.com/cloud-resource-manager?authuser=0) 

Chọn [Resources pending deletion](https://console.cloud.google.com/cloud-resource-manager?pendingDeletion=true&authuser=0) có thể lấy lai project đã lỡ xóa

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `yarn build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
