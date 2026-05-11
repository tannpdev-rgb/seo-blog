<!-- ## Triển khai (Deploy)

*   **GitHub Pages**: Sử dụng workflow `pages.yml` có sẵn.
*   **Vercel**: Cách dễ nhất, theo dõi tài liệu của Next.js.
*   **Netlify**: Hỗ trợ tốt các tính năng SSR, ISR của Next.js.
*   **Static hosting (S3, Firebase...)**: Chạy lệnh `EXPORT=1 UNOPTIMIZED=1 yarn build` để xuất ra thư mục `out`.

## Câu hỏi thường gặp (FAQ)
*   Làm thế nào để thêm component MDX tùy chỉnh?
*   Cách tùy chỉnh tìm kiếm kbar?
*   Triển khai với Docker.

## Hỗ trợ
Nếu anh thấy template này hữu ích, hãy ủng hộ bằng cách tặng một ngôi sao (star) trên GitHub hoặc trở thành nhà tài trợ.

## Giấy phép
[MIT](https://github.com/timlrx/tailwind-nextjs-starter-blog/blob/main/LICENSE) © [Timothy Lin](https://www.timlrx.com)

---

Hy vọng bản dịch này giúp íchChào anh Tấn, dưới đây là bản dịch toàn bộ nội dung tài liệu sang tiếng Việt để anh thuận tiện theo dõi cho các dự án của mình nhé:

---

![tailwind-nextjs-banner](/public/static/images/twitter-card.png)

# Tailwind Nextjs Starter Blog

[![GitHub Repo stars](https://img.shields.io/github/stars/timlrx/tailwind-nextjs-starter-blog?style=social)](https://GitHub.com/timlrx/tailwind-nextjs-starter-blog/stargazers/)
[![GitHub forks](https://img.shields.io/github/forks/timlrx/tailwind-nextjs-starter-blog?style=social)](https://github.com/timlrx/tailwind-nextjs-starter-blog/forks)
[![Twitter URL](https://img.shields.io/twitter/url?style=social&url=https%3A%2F%2Ftwitter.com%2Ftimlrxx)](https://x.com/timlrxx)
[![Sponsor](https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&link=https://github.com/sponsors/timlrx)](https://github.com/sponsors/timlrx)

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=https://github.com/timlrx/tailwind-nextjs-starter-blog)

Đây là một template khởi đầu cho blog sử dụng [Next.js](https://nextjs.org/) và [Tailwind CSS](https://tailwindcss.com/). Phiên bản 2 dựa trên thư mục Next App với [React Server Component](https://nextjs.org/docs/getting-started/react-essentials#server-components) và sử dụng [Contentlayer](https://www.contentlayer.dev/) để quản lý nội dung markdown.

Có lẽ đây là template blog markdown bằng Next.js giàu tính năng nhất hiện nay. Dễ dàng cấu hình và tùy chỉnh. Hoàn hảo để thay thế cho các blog cá nhân chạy bằng Jekyll và Hugo hiện có.

Kiểm tra tài liệu bên dưới để bắt đầu.

Gặp vấn đề? Hãy kiểm tra [trang FAQ](https://github.com/timlrx/tailwind-nextjs-starter-blog/wiki) và tìm kiếm các issue cũ. Đừng ngần ngại mở một issue mới nếu chưa có ai đăng trước đó.

Yêu cầu tính năng? Kiểm tra các thảo luận cũ để xem nó đã được nhắc đến chưa. Nếu chưa, hãy bắt đầu một luồng thảo luận mới. Mọi ý tưởng đều được chào đón!

## Các biến thể (Variations)

**Lưu ý**: Đây là các bản fork do cộng đồng đóng góp sử dụng các framework khác nhau hoặc có thay đổi đáng kể về mã nguồn - không được hỗ trợ chính thức.

*   Giải pháp thay thế bằng Astro - [Tailwind Astro Template](https://github.com/wanoo21/tailwind-astro-starting-blog).
*   Giải pháp thay thế bằng Remix-run - [Tailwind Remix-run Starter Blog Template](https://github.com/SangeetAgarwal/tailwind-remix-run-mdxjs-typescript-starter-blog).
*   Hỗ trợ đa ngôn ngữ (i18n) - [Template với i18n](https://tailwind-nextjs-starter-blog-i18n.vercel.app/) và [mã nguồn](https://github.com/PxlSyl/tailwind-nextjs-starter-blog-i18n/tree/main).

## Ví dụ Phiên bản 2 (Examples V2)

*(Phần này liệt kê danh sách các blog thực tế sử dụng template này, mình sẽ giữ nguyên tên chủ sở hữu và dịch mô tả ngắn gọn)*

*   **Demo Blog** - chính là repo này.
*   **Blog cá nhân của tôi (timlrx)** - đã chỉnh sửa để tự động tạo bài viết kèm ngày tháng.
*   **Karhdo's Blog** - Hành trình lập trình của Karhdo.
*   **SOTO's Blog** - Trang web cá nhân mang tính cá nhân hóa cao được nâng cấp từ V1.
*   **Prabhu's Blog** - Trang web cá nhân của Prabhu kèm blog.
*   **Rabby Hasan's Blog** - Blog cá nhân về phát triển full stack và điện toán đám mây.
*   **enscribe.dev** - Blog cá nhân về an ninh mạng, phát triển web frontend, v.v.
*   **dalelarroder.com** - Trang web cá nhân của Dale Larroder nâng cấp từ V1.
*   **thetalhatahir.com** - Blog của Talha Tahir. Thêm ảnh thu nhỏ bài viết, thẻ LinkedIn, nội dung hero đẹp mắt.
*   **homing.so** - Blog cá nhân của Homing về những thứ anh ấy đang học.
*   **zS1m's Blog** - Blog ghi chép và chia sẻ nội dung kỹ thuật hàng ngày.
*   **dariuszwozniak.net** - Blog về phát triển phần mềm.
*   **dreams.plus** - Trang blog ghi lại suy nghĩ về cuộc sống và công nghệ.
*   **francisaguilar.co blog** - Blog nói về công nghệ, thể hình và phát triển bản thân.
*   **Min71 Dev Blog** - Blog cá nhân về Blockchain, Phát triển phần mềm.
*   **Bryce Yu's Blog** - Blog về hệ thống phân tán, cơ sở dữ liệu và phát triển web.
*   **Remote Startup Senpai** - Landing page cho series anime Remote Startup Senpai.
*   **Secret Base** - Blog của Jac Hsu về công nghệ, tư duy và cuộc sống.
*   **Zsebinformatikus** - Blog hướng dẫn về xa lộ thông tin.
*   **Anton Morgunov's Blog** - Nói về khoa học không đơn giản hóa quá mức.
*   **Hans Blog** - Blog tiếng Trung về công nghệ frontend, phòng trưng bày và nhật ký du lịch.
*   **London Tech Talk** - Podcast khám phá xu hướng công nghệ và trải nghiệm sống xa xứ (Tiếng Nhật).
*   **CRUD Flow Blog** - Blog kỹ thuật về AI, Cloud, Khoa học dữ liệu.
*   **Trillium's Blog** - Chỉnh sửa để hiển thị PDF CV tại trang `/resume`.
*   **Wujie's Blog: 旅行者计划** - Khu vườn kỹ thuật số cá nhân của Wujie.
*   **Xiaodong's Blog** - Blog tiếng Trung về công nghệ frontend và cuộc sống.
*   **Azurtelier.com** - Trang web cá nhân về công nghệ, âm nhạc, minh họa AI.
*   **JoshHaines.com** - Trang web cá nhân của Josh Haines.
*   **Jigu's Blog** - Blog tiếng Trung về công nghệ, crypto, golang và cuộc sống.
*   **andrewsam.xyz** - Sử dụng ShadCN, Prisma, MongoDB, Auth.js, trang CV, dòng thời gian kinh nghiệm.
*   **Rulli Damara Putra's Portfolio** - Blog và portfolio cá nhân của Rully.
*   **blog.taoluyuan.com 套路猿** - Blog công nghệ hỗ trợ chuyển đổi nhiều giao diện.
*   **LyricsDecode.com** - Website lời bài hát với các tùy chọn xem tùy chỉnh.
*   **bmacharia.com** - Blog kỹ thuật về An ninh mạng và Quản trị rủi ro IT.
*   **armujahid.me** - Blog cá nhân của Abdul Rauf.
*   **leohuynh.dev** - 🇻🇳 Blog của Leo – câu chuyện, góc nhìn và ý tưởng. Thêm trang `/snippets`, `/books`, linh kiện `ProfileCard`, `CareerTimeline`.
*   **OpenSats Blog** - Tổ chức từ thiện công cộng tài trợ cho các dự án nguồn mở.
*   **Schedles Blog** - Mẹo lập kế hoạch truyền thông xã hội và cập nhật sản phẩm.
*   **YawDev Blog** - Blog về công nghệ và kinh doanh của đại lý IT.
*   **Engineering Notes** - Jonas Vetterle viết về kỹ thuật phần mềm, AI và Máy tính lượng tử.
*   **Screenager.dev** - Portfolio và Blog tài liệu hóa hành trình học tập.
*   **kezhenxu94's blog** - Viết về dev, mẹo, hướng dẫn.
*   **Parminder's blog** - Suy nghĩ về phát triển phần mềm và cuộc sống.
*   **wheelcircuit.com** - Tin tức và video YouTube về ô tô, cập nhật hàng ngày.
*   **taitrd.com** - Blog cá nhân của Tài về công nghệ, lập trình và thực hành Dynamodb.
*   **Shelton's Blog** - Chia sẻ kiến thức TypeScript full-stack (Next.js, React, Hono, Supabase).
*   **Culture DevOps** - Blog kỹ thuật về thực hành và công cụ DevOps.
*   **InnovateWire Blog** - Blog về tự động hóa phần mềm.
*   **MichaelScheiwiller.com** - Kết hợp kỹ thuật phần mềm và dữ liệu.
*   **Wahyu Ikbal** - Trang web cá nhân tích hợp AI, chia sẻ kiến thức công nghệ.
*   **ByteGeometry Blog** - Blog về xu hướng công nghệ và tăng trưởng kinh doanh.
*   **Farhad's Blog** - Chia sẻ tin tức công nghệ, tập trung vào AI và Khoa học dữ liệu.
*   **Utanzu Cybersecurity** - Cộng đồng đào tạo chuyên gia an ninh mạng.
*   **trungtmnguyen.com** - 🇻🇳 Blog cá nhân và kỹ thuật của Trung – mẹo, ý tưởng và bài học.
*   **Ryan Fitton's Blog** - Giao diện tùy chỉnh với phần 'Portfolio'.
*   **ktovoz.com** - Blog tiếng Trung chia sẻ cuộc sống và công nghệ.

Bạn đang sử dụng template này? Hãy thoải mái tạo PR và thêm blog của bạn vào danh sách.

## Động lực (Motivation)

Tôi muốn chuyển blog hiện tại của mình sang Nextjs và Tailwind CSS nhưng không có template sẵn có nào dễ dùng, vì vậy tôi quyết định tạo ra một cái. Thiết kế được phỏng theo blog của Tailwindlabs.

Tôi muốn nó giàu tính năng gần như các template blog phổ biến như [beautiful-jekyll](https://github.com/daattali/beautiful-jekyll) và [Hugo Academic](https://github.com/wowchemy/wowchemy-hugo-modules) nhưng sở hữu những gì tốt nhất của hệ sinh thái React và các thực hành phát triển web hiện đại.

## Tính năng (Features)

*   **Next.js với Typescript**
*   **Contentlayer** để quản lý logic nội dung
*   Dễ dàng tùy chỉnh phong cách với **Tailwind 3.0** và thuộc tính màu chủ đạo (primary color)
*   **MDX** - viết JSX ngay trong tài liệu markdown!
*   Điểm Lighthouse gần như hoàn hảo.
*   Nhẹ, chỉ **85kB** JS cho lần tải đầu tiên.
*   Thân thiện với thiết bị di động.
*   Chế độ sáng và tối (Light/Dark theme).
*   Tối ưu hóa font với `next/font`.
*   Tích hợp với **pliny** cung cấp:
    *   Nhiều tùy chọn phân tích (Analytics) như Umami, Plausible, Simple Analytics, Posthog và Google Analytics.
    *   Bình luận qua Giscus, Utterances hoặc Disqus.
    *   API bản tin (Newsletter) hỗ trợ Mailchimp, Buttondown, Convertkit, v.v.
    *   Tìm kiếm Command palette với Kbar hoặc Algolia.
*   Làm nổi bật cú pháp phía máy chủ (Server-side syntax highlighting) với số dòng qua `rehype-prism-plus`.
*   Hỗ trợ hiển thị toán học qua **KaTeX**.
*   Hỗ trợ trích dẫn và thư mục qua `rehype-citation`.
*   Thông báo kiểu Github (Github alerts).
*   Tối ưu hóa hình ảnh tự động qua `next/image`.
*   Hỗ trợ thẻ (tags) - mỗi thẻ duy nhất sẽ có trang riêng.
*   Hỗ trợ nhiều tác giả.
*   3 bố cục bài viết khác nhau.
*   2 bố cục danh sách bài viết khác nhau.
*   Hỗ trợ định tuyến lồng nhau cho các bài đăng.
*   Trang dự án (Projects page).
*   Cấu hình sẵn các tiêu đề bảo mật (security headers).
*   Thân thiện với SEO (RSS feed, sitemaps, v.v.).

## Hướng dẫn Bắt đầu Nhanh (Quick Start Guide)

1. Sao chép repo:
   ```bash
   npx degit 'timlrx/tailwind-nextjs-starter-blog'

```

2. Cá nhân hóa `siteMetadata.js` (thông tin liên quan đến trang web).
3. Sửa chính sách bảo mật nội dung trong `next.config.js` nếu muốn dùng trình phân tích khác.
4. Cá nhân hóa `authors/default.md` (tác giả chính).
5. Chỉnh sửa `projectsData.ts`.
6. Chỉnh sửa `headerNavLinks.ts` để tùy chỉnh các liên kết điều hướng.
7. Thêm bài viết blog.
8. Triển khai lên Vercel.

## Cài đặt (Installation)

```bash
yarn

```

*Lưu ý: Nếu dùng Windows, bạn có thể cần chạy: `$env:PWD = $(Get-Location).Path*`

## Phát triển (Development)

Chạy server phát triển:

```bash
yarn dev

```

Mở [http://localhost:3000]() trên trình duyệt. Các thay đổi sẽ được cập nhật ngay lập tức (live reloading).

## Mở rộng / Tùy chỉnh (Extend / Customize)

* `data/siteMetadata.js`: Chứa hầu hết thông tin trang web.
* `data/authors/default.md`: Thông tin tác giả mặc định.
* `data/projectsData.js`: Dữ liệu cho trang dự án.
* `data/headerNavLinks.js`: Các liên kết điều hướng.
* `data/logo.svg`: Thay thế bằng logo của anh.
* `data/blog`: Thay thế bằng các bài viết của anh.
* `public/static`: Lưu trữ tài sản như hình ảnh, favicon.
* `tailwind.config.js` và `css/tailwind.css`: Cấu hình giao diện.
* `components/MDXComponents.js`: Thêm các component JSX/React tùy chỉnh để dùng trong file `.mdx`.
* `layouts`: Các template chính cho trang (PostLayout, PostSimple, PostBanner, v.v.).

## Bài viết (Post)

Nội dung được mô hình hóa bằng **Contentlayer**.

### Frontmatter (Phần đầu bài viết)

Tuân theo tiêu chuẩn của Hugo. Ví dụ:

```yaml
---
title: 'Giới thiệu Tailwind Nextjs Starter Blog'
date: '2021-01-12'
tags: ['next-js', 'tailwind', 'guide']
draft: false
summary: 'Mô tả ngắn về bài viết...'
authors: ['default']
layout: PostLayout
---

```

## Triển khai (Deploy)

* **GitHub Pages**: Sử dụng workflow `pages.yml` có sẵn.
* **Vercel**: Cách dễ nhất, theo dõi tài liệu của Next.js.
* **Netlify**: Hỗ trợ tốt các tính năng SSR, ISR của Next.js.
* **Static hosting (S3, Firebase...)**: Chạy lệnh `EXPORT=1 UNOPTIMIZED=1 yarn build` để xuất ra thư mục `out`.

## Câu hỏi thường gặp (FAQ)

* Làm thế nào để thêm component MDX tùy chỉnh?
* Cách tùy chỉnh tìm kiếm kbar?
* Triển khai với Docker.

## Hỗ trợ

Nếu anh thấy template này hữu ích, hãy ủng hộ bằng cách tặng một ngôi sao (star) trên GitHub hoặc trở thành nhà tài trợ.

## Giấy phép

[MIT]() © [Timothy Lin]()

--- -->