---
title: شبکه‌ها
description: مروری بر شبکه‌های اتریوم و محل دریافت اتر (ETH) شبکه‌ی تست برای آزمایش برنامه‌ی خود.
lang: fa
sidebar: true
---

از آنجایی که اتریوم یک پروتکل است، این بدان معناست که می‌تواند چندین «شبکه» مستقل مطابق با این پروتکل وجود داشته باشند که با یکدیگر تعامل نداشته باشند.

شبکه‌ها محیط‌های مختلف اتریوم هستند که می‌توانید برای توسعه، آزمایش یا تولید به آن‌ها دسترسی داشته باشید. حساب اتریوم شما در شبکه‌های مختلف کار می‌کند، اما موجودی حساب و سابقه‌ی تراکنش‌های شما از شبکه اصلی اتریوم منتقل نمی‌شود. برای اهداف آزمایشی، دانستن اینکه کدام شبکه‌ها در دسترس هستند و چگونه می‌توان اتر شبکه تست را برای استفاده دریافت کرد مفید است.

## پیش‌نیازها {#prerequisites}

قبل از مطالعه در مورد شبکه‌های مختلف باید اصول اولیه اتریوم را بدانید، چون شبکه‌های تست نسخه‌ای ارزان و ایمن از اتریوم را برای کار در اختیار شما قرار می‌دهند. [معرفی اتریوم](/developers/docs/intro-to-ethereum/) ما را امتحان کنید.

## شبکه‌های عمومی {#public-networks}

شبکه‌های عمومی برای هر کسی در جهان با اتصال به اینترنت قابل‌دسترسی هستند. هر کسی می‌تواند تراکنش‌هایی را در یک زنجیره‌ی بلوکی عمومی بخواند یا ایجاد کند و تراکنش‌های در حال اجرا را تأیید کند. توافق در مورد تراکنش‌ها و وضعیت شبکه با اجماع همتایان تعیین می‌شود.

### شبکه‌ی اصلی {#mainnet}

شبکه‌ی اصلی اولین زنجیره‌ی بلوکی عمومی تولید اتریوم است که تراکنش‌های توزیع شده با ارزش واقعی در دفتر کل روی آن انجام می‌شود.

وقتی مردم و صرافی‌ها درباره قیمت اتر صحبت می‌کنند، در مورد اتر روی شبکه‌ی اصلی صحبت می‌کنند.

### شبکه‌ی تست {#testnets}

علاوه بر شبکه اصلی، شبکه‌های آزمایشی عمومی نیز وجود دارند. علاوه بر شبکه‌ی اصلی، شبکه‌های آزمایشی عمومی نیز وجود دارند. این را به‌عنوان یک آنالوگ برای تولید در مقابل سرورهای مرحله‌ای در نظر بگیرید.

به‌طور کلی مهم است که هر کد قراردادی را که در یک شبکه‌ی آزمایشی می‌نویسید قبل از استقرار در شبکه‌ی اصلی آزمایش کنید. اگر در حال ساختن برنامه‌ای هستید که با قراردادهای هوشمند موجود ادغام می‌شود، اکثر پروژه‌ها نسخه‌هایی را در شبکه‌های آزمایشی مستقر کرده‌اند که می‌توانید با آنها تعامل داشته باشید.

بیشتر شبکه‌های آزمایشی از مکانیزم اجماع اثبات اعتبار استفاده می‌کنند. این بدان معناست که تعداد کمی از گره‌ها برای اعتبارسنجی تراکنش‌ها و ایجاد بلوک‌های جدید انتخاب می‌شوند و هویت آن‌ها در این فرایند سهام‌گذاری می‌شود. ایجاد انگیزه برای استخراج در یک شبکه‌ی آزمایشی اثبات کار که می‌تواند آن را آسیب‌پذیر کند، دشوار است.

اتر شبکه‌ی تست ارزش واقعی ندارد، بنابراین هیچ بازاری برای اتر شبکه‌ی تست وجود ندارد. از آنجایی که برای تعامل واقعی با اتریوم به اتر نیاز دارید، اکثر مردم اتر شبکه‌ی تست را از فاست‌ها دریافت می‌کنند. بیشتر فاست‌ها برنامه‌های تحت وب هستند که می‌توانید آدرسی را که درخواست ارسال اتر به آن آدرس را دارید در آن‌ها وارد کنید.

#### Arbitrum Rinkeby {#arbitrum-rinkeby}

یک شبکه‌ی تست برای [‏Arbitrum‏](https://arbitrum.io/).

##### فاست‌های Arbitrum Rinkeby

- [FaucETH](https://fauceth.komputing.org) (فاست چند زنجیره‌ای بدون نیاز به داشتن حساب اجتماعی)
- [فاست Chainlink](https://faucets.chain.link/)
- [فاست Paradigm](https://faucet.paradigm.xyz/)

#### Görli {#goerli}

یک شبکه‌ی تست اثبات اعتبار که بین کلاینت‌ها کار می‌کند.

##### فاست‌های Görli

- [فاست Görli](https://faucet.goerli.mudit.blog/)
- [فاست Chainlink](https://faucets.chain.link/)
- [Alchemy Goerli Faucet](https://goerlifaucet.com/)

#### Kintsugi {#kintsugi}

یک شبکه‌ی تست ادغامی برای اتریوم.

##### فاست‌های Kintsugi

- [FaucETH](https://fauceth.komputing.org) (فاست چندزنجیره‌ای بدون نیاز به داشتن حساب اجتماعی)
- [فاست‌ Kintsugi](https://faucet.kintsugi.themerge.dev/)

#### Kovan {#kovan}

یک شبکه‌ی تست اثبات اعتبار برای کسانی که از کلاینت‌های OpenEthereum استفاده می‌کنند.

##### فاست‌های Kovan

- [FaucETH](https://fauceth.komputing.org) (فاست چندزنجیره‌ای بدون نیاز به داشتن حساب اجتماعی)
- [فاست Kovan](https://faucet.kovan.network/)
- [فاست Chainlink](https://faucets.chain.link/)
- [فاست Paradigm](https://faucet.paradigm.xyz/)

#### Optimistic Kovan {#optimistic-kovan}

یک شبکه‌ی تست برای [Optimism](https://www.optimism.io/).

##### فاست‌های Optimistic Kovan

- [FaucETH](https://fauceth.komputing.org) (فاست چندزنجیره‌ای بدون نیاز به داشتن حساب اجتماعی)
- [فاست Paradigm](https://faucet.paradigm.xyz/)

#### Rinkeby {#rinkeby}

یک شبکه‌ی تست اثبات اعتبار برای کسانی که از کلاینت Geth استفاده می‌کنند.

##### فاست‌های Rinkeby

- [FaucETH](https://fauceth.komputing.org) (فاست چندزنجیره‌ای بدون نیاز به داشتن حساب اجتماعی)
- [فاست Alchemy](https://RinkebyFaucet.com)
- [فاست Chainlink](https://faucets.chain.link/)
- [فاست Paradigm](https://faucet.paradigm.xyz/)
- [فاست Rinkeby](https://faucet.rinkeby.io/)

#### Ropsten {#ropsten}

یک شبکه‌ی تست اثبات کار. این به این معنی است که این فاست بهترین بازنمایی مشابه اتریوم است.

##### فاست‌های Ropsten

- [FaucETH](https://fauceth.komputing.org) (فاست چندزنجیره‌ای بدون نیاز به داشتن حساب اجتماعی)
- [فاست Paradigm](https://faucet.paradigm.xyz/)

## شبکه‌های خصوصی {#private-networks}

یک شبکه‌ی اتریوم در صورتی که گره‌های آن به یک شبکه‌ی عمومی متصل نباشند یک شبکه‌ی خصوصی است (یعنی شبکه‌ی اصلی یا شبکه‌ی تست). در این زمینه، خصوصی فقط به معنای رزرو شده یا جدا شده است، نه محافظت‌شده یا امن.

### شبکه‌های توسعه {#development-networks}

برای اینکه یک برنامه‌ی کاربردی اتریوم را توسعه دهید، لازم است آن را در یک شبکه‌ی خصوصی اجرا کنید تا قبل از بکارگیری نحوه‌ی کارکرد آن را ببینید. مشابه نحوه‌ی ایجاد یک سرور محلی در رایانه خود برای توسعه‌ی وب، می‌توانید یک نمونه زنجیره‌ی بلوکی محلی برای آزمایش dapp خود ایجاد کنید. این موضوع امکان تکرار بسیار سریع‌تر را نسبت به یک شبکه‌ی تست عمومی فراهم می‌کند.

پروژه‌ها و ابزارهایی برای کمک به این امر اختصاص داده شده است. درباره‌ی [شبکه‌های توسعه](/developers/docs/development-networks/) بیشتر بدانید.

### شبکه‌های کنسرسیومی {#consortium-networks}

فرایند اجماع توسط مجموعه‌ای از گره‌های از پیش تعریف‌شده که قابل‌اعتماد هستند کنترل می‌شود. به‌عنوان مثال، یک شبکه‌ی خصوصی از مؤسسات دانشگاهی شناخته‌شده که هر یک گره‌ای واحد را حکمرانی می‌کنند و بلوک‌ها توسط آستانه‌ای از امضاکنندگان در شبکه اعتبارسنجی می‌شوند.

اگر یک شبکه‌ی عمومی اتریوم مانند اینترنت عمومی است، می‌توانید یک شبکه‌ی کنسرسیومی را به‌عنوان یک اینترانت خصوصی در نظر بگیرید.

## ابزارهای مرتبط {#related-tools}

- [‏Chainlist‏](https://chainlist.org/) _فهرست شبکه‌های EVM برای اتصال کیف پول‌ها و ارائه‌دهندگان به شناسه‌ی زنجیره و شناسه‌ی شبکه‌ی مناسب_
- [زنجیره‌های مبتنی بر EVM](https://github.com/ethereum-lists/chains) _مخزن فراداده‌های زنجیره‌ای گیت‌هاب که Chainlist را تقویت می‌کند_

## بیشتر بخوانید {#further-reading}

_آیا منبعی اجتماعی می‌شناسید که به شما کمک کرده باشد؟ این صفحه را ویرایش کنید و آن را اضافه کنید!_
