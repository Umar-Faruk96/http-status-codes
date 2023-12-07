# HTTP-response-status-codes

[HTTP response status code](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status) হল, ব্রাউজার থেকে কোন ডাটা সার্ভারে রিকুয়েস্ট করার পর সার্ভার কর্তৃক সেই রিকুয়েস্টকে কেন্দ্র করে বিভিন্ন ধরণের অপারেশন চালানোর প্রেক্ষিতে প্রাপ্ত ফলাফল বা রেসপন্স ব্রাউজারের কাছে পাঠানোর জন্য তিন সংখ্যার যে সাংকেতিক কোড সার্ভার ব্যবহার করে তাকে বলে।

সার্ভার থেকে প্রাপ্ত এই রেসপন্সগুলো পাঁচ ভাগে বিভক্ত। ফলে তিন সংখ্যার এই সাংকেতিক কোডের প্রথম সংখ্যাটি 1 থেকে 5, এই রেঞ্জের ভেতরে হয়। অতঃপর 1xx থেকে 5xx এই প্যাটার্নে আরো দুটি সংখ্যা যোগ হয়, যেমনঃ `404 error!`।

## পাঁচ ভাগে বিভক্ত রেসপন্সগুলো হলঃ

1. [Informational responses](#information_responses) (100 – 199)
2. [Successful responses](#successful_responses) (200 – 299)
3. [Redirection messages](#redirection_messages) (300 – 399)
4. [Client error responses](#client_error_responses) (400 – 499)
5. [Server error responses](#server_error_responses) (500 – 599)

একে একে সবগুলোর রেসপন্স কোডগুলো সম্পর্কে জানি।

## Information responses{#information_responses}

[`100 Continue`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/100)

এই রেসপন্স কোডটির মানে হল, ক্লায়েন্ট বা ব্রাউজার রিকুয়েস্ট পাঠানো কন্টিনিউ করবে। আর যদি রিকুয়েস্ট ইতিমধ্যেই সম্পন্ন হয়ে যায় তখন প্রাপ্ত রেসপন্সকে ইগনোর করবে।

[`101 Switching Protocols`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/101)

এই রেসপন্স কোডটি সার্ভার প্রদান করে তখন যখন ব্রাউজারের তরফ থেকে কোন রিকুয়েস্টকে আপগ্রেড করার জন্য হেডারের মাধ্যমে মেসেজ প্রেরণ করা হয়। মেসেজটি গৃহীত হয়েছে এবং সার্ভার সে অনুযায়ী একশন নিয়ে নির্ধারিত প্রটোকলে পরিবর্তিত হওয়ার প্রক্রিয়াটি সম্পন্ন করছে বোঝাতে এই কোডটি ব্যবহৃত হয়।

[`102 Processing`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/102)

[`103 Early Hints`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/103)

## Successful responses{#successful_responses}

[`200 OK`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/200)

[`201 Created`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/201)

[`202 Accepted`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/202)

[`203 Non-Authoritative Information`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/203)

[`204 No Content`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/204)

[`206 Partial Content`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/206)

[`207 Multi-Status`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/207)

[`208 Already Reported`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/208)

[`226 IM Used`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/226)

## Redirection messages{#redirection_messages}

[`300 Multiple Choices`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/300)

[`301 Moved Permanently`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/301)

[`302 Found`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/302)

[`303 See Other`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/303)

[`304 Not Modified`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/304)

[`305 Use Proxy`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status#305_use_proxy)

[`306 unused`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status#306_unused)

[`307 Temporary Redirect`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/307)

[`308 Permanent Redirect`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/308)

## Client error responses{#client_error_responses}

[`400 Bad Request`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/400)

[`401 Unauthorized`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/401)

[`402 Payment Required`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/402)

[`403 Forbidden`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/403)

[`404 Not Found`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/404)

[`405 Method Not Allowed`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/405)

[`406 Not Acceptable`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/406)

[`407 Proxy Authentication Required`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/407)

[`408 Request Timeout`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/408)

[`409 Conflict`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/409)

[`410 Gone`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/410)

[`411 Length Required`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/411)

[`412 Precondition Failed`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/412)

[`413 Payload Too Large`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/413)

[`414 URI Too Long`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/414)

[`415 Unsupported Media Type`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/415)

[`416 Range Not Satisfiable`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/416)

[`417 Expectation Failed`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/417)

[`418 I'm a teapot`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/418)

[`421 Misdirected Request`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/421)

[`422 Unprocessable Content`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/422)

[`423 Locked`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/423)

[`424 Failed Dependency`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/424)

[`425 Too Early`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/425)

[`426 Upgrade Required`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/426)

[`428 Precondition Required`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/428)

[`429 Too Many Requests`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/429)

[`431 Request Header Fields Too Large`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/431)

[`451 Unavailable For Legal Reasons`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/451)

## Server error responses{#server_error_responses}

[`500 Internal Server Error`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/500)

[`501 Not Implemented`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/501)

[`502 Bad Gateway`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/502)

[`503 Service Unavailable`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/503)

[`504 Gateway Timeout`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/504)

[`505 HTTP Version Not Supported`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/505)

[`506 Variant Also Negotiates`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/506)

[`507 Insufficient Storage`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/507)

[`508 Loop Detected`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/508)

[`510 Not Extended`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/510)

[`511 Network Authentication Required`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/511)
