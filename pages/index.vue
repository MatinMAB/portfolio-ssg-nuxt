<template lang="">
  <div>
    <div class="md:container mx-auto px-6">
      <div class="grid grid-cols-12 mt-12 gap-4">
        <div class="col-span-4">
          <div class="flex flex-col justify-center items-center gap-6">
            <div class="">
              <img
                src="../assets/avatar.png"
                class="mx-auto w-32 rounded-full border-8 border-gray-200"
              />
            </div>
            <div class="flex justify-center items-center gap-3">
              <InstagramSvg class="w-8 text-purple-500 cursor-pointer" />
              <GithubSvg class="w-8 text-black-500 cursor-pointer" />
              <TelegramSvg class="w-8 text-blue-500 cursor-pointer" />
              <WhatsappSvg class="w-8 text-green-500 cursor-pointer" />
            </div>
          </div>
        </div>
        <div
          class="col-span-8 p-4 flex justify-center gap-2 flex-col border-r-4 bg-gradient-to-r from-gray-300 to-white"
        >
          <p>مشخصات :<span class="text-indigo-500">Matin MAB</span></p>
          <p>
            <code class="text-green-600">{{ front }}</code>
          </p>
          <p>ایمیل : <span class="text-red-400">MatinMAB789@gmail.com</span></p>
          <p>شماره تماس : <span class="text-red-700">9722 691 935 98+</span></p>
        </div>
      </div>
      <div class="mt-24">
        <h1 class="text-3xl border-b-2 border-gray-200 pb-2">مهارت ها</h1>
        <div class="flex justify-between items-center p-8 gap-2">
          <HtmlSvg class="w-20 text-pink-500 cursor-pointer" />
          <CssSvg class="w-24 mb-4 text-pink-500 cursor-pointer" />
          <JavascriptSvg class="w-20 text-green-400 cursor-pointer" />
          <JquerySvg class="w-20 text-green-400 cursor-pointer" />
          <SassSvg class="w-20 text-pink-500 cursor-pointer" />
          <BootstrapSvg class="w-20 text-purple-500 cursor-pointer" />
          <TailwindSvg class="w-20 text-blue-400 cursor-pointer" />
          <BulmaSvg class="w-20 text-green-400 cursor-pointer" />
        </div>
        <h1
          class="text-2xl border-b-2 border-green-500 pb-2 mx-8 text-green-500 mt-8"
        >
          Vue JS
        </h1>
        <div class="flex justify-center items-center p-8 gap-36">
          <VueSvg class="w-20 text-green-500 cursor-pointer" />
          <VuetifySvg class="w-20 text-blue-500 cursor-pointer" />
          <NuxtSvg class="w-20 text-green-600 cursor-pointer" />
        </div>
        <h1 class="text-2xl border-b-2 border-blue-400 pb-2 mx-8 text-blue-400">
          React Js
        </h1>
        <div class="flex justify-center items-center p-8 gap-36">
          <ReactSvg class="w-20 text-blue-400 cursor-pointer" />
          <ReduxSvg class="w-20 text-purple-600 cursor-pointer" />
        </div>
        <h1
          class="text-2xl border-b-2 border-yellow-400 pb-2 mx-8 text-yellow-500"
        >
          در حال یادگیری ...
        </h1>
        <div class="flex justify-center items-center p-8 gap-36">
          <NextSvg class="w-20 text-black cursor-pointer" />
          <MaterialuiSvg class="w-20 cursor-pointer" />
        </div>
        <h1 class="text-3xl border-b-2 border-black pb-2 mt-24 mb-16">
          نمونه کار ها
        </h1>
        <div class="grid-cols-1 md:grid-cols-2 lg:grid-cols-3 grid gap-8 mb-16">
          <div
            class="bg-gray-50 border-2 border-gray-400 p-2 rounded-xl shadow-md hover:shadow-xl transition-all overflow-hidden"
          >
            <img src="../assets/shopVue.png" class="rounded-xl" />
            <p class="text-center my-4 text-lg">سایت فروشگاهی</p>
            <p class="text-center my-4 text-md">
              <span class="text-green-500">Vue - Vuex - VueRouter</span>
            </p>
            <p class="text-center my-4 text-md text-gray-500">
              برای مشاهده سایت
              <a
                href="https://myportfo-ecommerce.netlify.app/"
                target="_blank"
                class="text-blue-400"
                >اینجا</a
              >
              کلیک کنید
            </p>
            <p class="text-center my-4 text-md text-gray-500">
              مشاهده کدهای نوشته شده در
              <a
                href="https://github.com/MatinMAB/Ecommerce-Portfolio"
                target="_blank"
                class="text-gray-400"
                >گیت هاب</a
              >
            </p>
          </div>
          <div
            class="bg-gray-50 border-2 border-gray-400 p-2 rounded-xl shadow-md hover:shadow-xl transition-all"
          >
            <img src="../assets/panelvuetify.png" class="rounded-xl" />
            <p class="text-center my-4 text-lg">
              پنل ادمین - فرم ورود با اعتبار سنجی
            </p>
            <p class="text-center my-4 text-md">
              <span class="text-green-500">Vue - VueRouter - Vuetify</span>
            </p>
            <p class="text-center my-4 text-md text-gray-500">
              برای مشاهده سایت
              <a
                href="https://myportfo-adminpanel.netlify.app/"
                target="_blank"
                class="text-blue-400"
                >اینجا</a
              >
              کلیک کنید
            </p>
            <p class="text-center my-4 text-md text-gray-500">
              مشاهده کدهای نوشته شده در
              <a
                href="https://github.com/MatinMAB/Admin-Panel-Portfolio"
                target="_blank"
                class="text-gray-400"
                >گیت هاب</a
              >
            </p>
          </div>

          <div
            class="bg-gray-50 border-2 border-gray-400 p-2 rounded-xl shadow-md hover:shadow-xl transition-all"
          >
            <img src="../assets/portfolio.png" class="rounded-xl" />
            <p class="text-center my-4 text-lg">
              سایت مهارت ها و نمونه کارهای من
            </p>
            <p class="text-center my-4 text-md">
              <span class="text-green-500">Vue - Nuxt (SSG App)</span>
            </p>
            <p class="text-center my-4 text-md text-gray-500">
              برای مشاهده سایت
              <a
                href="https://matinmab-portfolio.netlify.app/"
                target="_blank"
                class="text-blue-400"
                >اینجا</a
              >
              کلیک کنید
            </p>
            <p class="text-center my-4 text-md text-gray-500">
              مشاهده کدهای نوشته شده در
              <a
                href="https://github.com/MatinMAB/portfolio-ssg-nuxt"
                target="_blank"
                class="text-gray-400"
                >گیت هاب</a
              >
            </p>
          </div>
          <div
            class="bg-gray-50 border-2 border-gray-400 p-2 rounded-xl shadow-md hover:shadow-xl transition-all"
          >
            <img src="../assets/exchange.png" class="rounded-xl" />
            <p class="text-center my-4 text-lg">سایت قیمت ارزهای دیجیتال</p>
            <p class="text-center my-4 text-md">
              <span class="text-green-500">React - Rest API</span>
            </p>
            <p class="text-center my-4 text-md text-gray-500">
              برای مشاهده سایت
              <a
                href="https://exchange-react-simple-app.netlify.app/"
                target="_blank"
                class="text-blue-400"
                >اینجا</a
              >
              کلیک کنید
            </p>
            <p class="text-center my-4 text-md text-gray-500">
              مشاهده کدهای نوشته شده در
              <a
                href="https://github.com/MatinMAB/exchange-app"
                target="_blank"
                class="text-gray-400"
                >گیت هاب</a
              >
            </p>
          </div>
          <div
            class="bg-gray-50 border-2 border-gray-400 p-2 rounded-xl shadow-md hover:shadow-xl transition-all"
          >
            <img src="../assets/social.png" class="rounded-xl" />
            <p class="text-center my-4 text-lg">
              نمونه ای از یک شبکه اجتماعی پیامرسان
            </p>
            <p class="text-center my-4 text-md">
              <span class="text-green-500"
                >React - React Router Dom v6 - React Chat Engine</span
              >
            </p>
            <p class="text-center my-4 text-md text-gray-500">
              برای مشاهده سایت
              <a
                href="https://my-social-react-media.netlify.app/"
                target="_blank"
                class="text-blue-400"
                >اینجا</a
              >
              کلیک کنید
            </p>
            <p class="text-center my-4 text-md text-gray-500">
              مشاهده کدهای نوشته شده در
              <a
                href="https://github.com/MatinMAB/social-media"
                target="_blank"
                class="text-gray-400"
                >گیت هاب</a
              >
            </p>
          </div>
          <div
            class="bg-gray-50 border-2 border-gray-400 p-2 rounded-xl shadow-md hover:shadow-xl transition-all"
          >
            <img src="../assets/cart.png" class="rounded-xl" />
            <p class="text-center my-4 text-lg">
              سبد خرید یک سایت ساده فروشگاهی
            </p>
            <p class="text-center my-4 text-md">
              <span class="text-green-500"
                >React - React Router Dom v6 - using Context</span
              >
            </p>
            <p class="text-center my-4 text-md text-gray-500">
              برای مشاهده سایت
              <a
                href="https://cart-react-site.netlify.app/"
                target="_blank"
                class="text-blue-400"
                >اینجا</a
              >
              کلیک کنید
            </p>
            <p class="text-center my-4 text-md text-gray-500">
              مشاهده کدهای نوشته شده در
              <a
                href="https://github.com/MatinMAB/social-media"
                target="_blank"
                class="text-gray-400"
                >گیت هاب</a
              >
            </p>
          </div>
          <div
            class="bg-gray-50 border-2 border-gray-400 p-2 rounded-xl shadow-md hover:shadow-xl transition-all"
          >
            <img src="../assets/login.png" class="rounded-xl" />
            <p class="text-center my-4 text-lg">
              فرم ثبت نام و ورود به همراه اعتبار سنجی
            </p>
            <p class="text-center my-4 text-md">
              <span class="text-green-500">React - React Router Dom v5</span>
            </p>
            <p class="text-center my-4 text-md text-gray-500">
              برای مشاهده سایت
              <a
                href="https://valid-form-react.netlify.app/"
                target="_blank"
                class="text-blue-400"
                >اینجا</a
              >
              کلیک کنید
            </p>
            <p class="text-center my-4 text-md text-gray-500">
              مشاهده کدهای نوشته شده در
              <a
                href="https://github.com/MatinMAB/login-app"
                target="_blank"
                class="text-gray-400"
                >گیت هاب</a
              >
            </p>
          </div>
        </div>
      </div>
    </div>
    <div class="text-center bg-gray-100 h-20 flex flex-col justify-center items-center gap-2">
      <h2>طراحی شده توسط <span class="text-blue-500">Matin_MAB</span></h2>
      <h2>2021 - 1400</h2>
    </div>
  </div>
</template>
<script>
export default {
  name: "IndexPage",
  data: () => ({
    front: "</ Front-End Developer >",
  }),
};
</script>
