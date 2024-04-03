<template>
  <main class="w-full md:w-2/3 lg:w-3/4 px-6 mx-auto text-white">
    <header>
    <NuxtLink to="/">
        <img src="/logo.jpg" class="w-48 mx-auto" alt="logo">
      </NuxtLink>
      <nav class="w-full flex justify-between items-center p-3 bg-white bg-opacity-10 my-5 rounded-xl">
        <NuxtLink class="text-white text-2xl hover:bg-blue-400 py-2 px-5 duration-300 ease-in-out cursor-pointer rounded-md">
          Home
        </NuxtLink>
        <NuxtLink class="text-white text-2xl hover:bg-blue-400 py-2 px-5 duration-300 ease-in-out cursor-pointer rounded-md">
          About
        </NuxtLink>
        <NuxtLink class="text-white text-2xl hover:bg-blue-400 py-2 px-5 duration-300 ease-in-out cursor-pointer rounded-md">
          Contract
        </NuxtLink>
      </nav>
    </header>
    <section>
      <UiTypographyP>COMMUNITY TAKEOVER</UiTypographyP>
      <UiTypographyH1>KISHU INU ON SOL</UiTypographyH1>
      <UiTypographyP>Kishu Inu aims to disrupt the traditional financial system by leveraging blockchain technology and creating a decentralized ecosystem that empowers users and eliminates the need for intermediaries. Through transparency and immutability, Kishu Inu ensures that all transactions are secure and verifiable, making it a trusted and reliable platform for users to engage in financial activities.</UiTypographyP>
      <div class="flex gap-5 w-auto">
        <NuxtLink to="https://t.me/kishuinuonsolana" class="w-auto px-5 py-3 bg-blue-400 hover:bg-blue-300 justify-center duration-300 ease-in-out rounded-xl outline-none focus:outline-none flex items-center gap-4">
          <IconsTelegram class="w-7 h-7 text-white " />
          <UiTypographyP>Join Telegram</UiTypographyP>
        </NuxtLink>
        <NuxtLink to="https://twitter.com/kishuonsola/" class="w-auto px-5 py-3 bg-blue-400 hover:bg-blue-300 justify-center duration-300 ease-in-out rounded-xl outline-none focus:outline-none flex items-center gap-4">
          <IconsTwitter class="w-7 h-7 text-white " />
          <UiTypographyP>Follow on Twitter</UiTypographyP>
        </NuxtLink>
      </div>
      <ul class="grid my-10 gap-8">
        <li class="border border-white p-5 rounded-tl-2xl rounded-br-2xl">
          <h2 class="saiyan text-6xl text-blue-400">MISSION AND VISION</h2>
          <UiTypographyP>The community behind Kishu Inu is a passionate and dedicated group of individuals who believe in the potential of cryptocurrency to revolutionize the way we interact with money. By fostering a sense of collaboration and inclusivity, Kishu Inu is building a strong and vibrant community that is committed to pushing the boundaries of what is possible in the world of decentralized finance.
          <br/><br/>
          Whether you're a seasoned crypto investor or new to the space, Kishu Inu offers something for everyone. With its low fees, fast transaction speeds, and innovative features, Kishu Inu is poised to become a leader in the decentralized finance space. Join the movement today and be a part of the future of finance with Kishu Inu on Sol!</UiTypographyP>
        </li>
        <li class="border border-white p-5 rounded-tl-2xl rounded-br-2xl">
          <h2 class="saiyan text-6xl text-blue-400">Tokenomics</h2>    
          <UiTypographyP>Liquidity pool 100% burnt<br/><br/>
          Community Takeover<br/><br/>
          No team token</UiTypographyP>
        </li>
      </ul>
    </section>
    <section>
      <UiTypographyH1 class="saiyan text-center">Roadmap</UiTypographyH1>
      <ul class="grid gap-10 lg:grid-cols-3 mt-10">
        <li class="border border-white p-5 rounded-tl-2xl rounded-br-2xl">
          <h2 class="saiyan text-6xl text-blue-400">Phase One</h2>
          <UiTypographyP class="mt-3">
            Community takeover<br  />
            New Telegram<br  />
            Website<br  />
            Whitepaper
          </UiTypographyP>
        </li>
        <li class="border border-white p-5 rounded-tl-2xl rounded-br-2xl">
          <h2 class="saiyan text-6xl text-blue-400">Phase Two</h2>
          <UiTypographyP class="mt-3">
            Dexscreener update<br  />
            SOL trending<br  />
            Marketing<br  />
            AMA
          </UiTypographyP>
        </li>
        <li class="border border-white p-5 rounded-tl-2xl rounded-br-2xl">
          <h2 class="saiyan text-6xl text-blue-400">Phase Three</h2>
          <UiTypographyP class="mt-3">
            Partnership<br />
            Twitter space<br />
            Utility announcement <br />
            Aggressive marketing
          </UiTypographyP>
        </li>
      </ul>
    </section>
    <footer class="grid place-items-center mt-10">
      <div class="flex gap-5">
        <NuxtLink to="https://t.me/kishuinuonsolana" class="w-12 aspect-square bg-blue-400 hover:bg-blue-300 justify-center duration-300 ease-in-out rounded-full outline-none focus:outline-none flex items-center gap-4">
          <IconsTelegram class="w-7 h-7 text-white " />
        </NuxtLink>
        <NuxtLink to="https://twitter.com/kishuonsola/" class="w-12 aspect-square bg-blue-400 hover:bg-blue-300 justify-center duration-300 ease-in-out rounded-full outline-none focus:outline-none flex items-center gap-4">
          <IconsTwitter class="w-7 h-7 text-white " />
        </NuxtLink>
      </div>
      <UiTypographyP class="mt-2">&copy;Kishu Inu, {{new Date().getFullYear()}}</UiTypographyP>
  </footer>
  </main>
</template>
<style>
@import url('https://fonts.cdnfonts.com/css/saiyan-sans');
@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');
body {
  font-family: 'Roboto', sans-serif;
  background-size: cover;
  background-position: center;
  padding: 3rem 0;
  background: black;
}
* {
  box-sizing: border-box;
}
.saiyan {
  font-family: 'Saiyan Sans', sans-serif;
}

.background {
  background-image: url('/beerus-profile-pic.png');
  background-size: cover;
  background-repeat: no-repeat;
  background-position: top;
  background-position: center;
}
</style>
