<script>
import { ref } from "vue";
export default {

};
</script>
<script setup>
import CounterVue from "../component/Counter.vue";
import SkillVue from "../component/Skill.vue";
</script>
<template>
  <h2
    class="text-[14px] font-medium text-[#aaaaaa] tracking-[2px] after:content-[''] after:w-[120px] after:h-[1px] after:inline-block after:bg-green-600 after:ml-[4px] after:mb-[3px]"
  >
    ABOUT
  </h2>
  <p class="text-white text-[36px] font-bold mb-[15px]">LEARN MORE ABOUT ME</p>
  {/* Section Contants */}
  <div class="grid grid-cols-12">
    <div class="col-span-4 pr-[24px]">
      <img src="me.jpg" alt="not found" class="w-[100%]" />
    </div>
    <div class="col-span-8">
      <h2
        class="font-bold text-[26px] text-[#18d26e] font-[Raleway, sans-serif] mb-[8px]"
      >
        Blockchain Specialist & Full Stack Expert
      </h2>
      <div class="flex grid grid-cols-2">
        <div class="col-span-1">
          <ul>
            <li class="pb-[10px] text-white">
              <i class="icofont-rounded-right text-[#18d26e]"></i>
              <strong class="text-white">Birthday:</strong> 20 Jan 1991
            </li>
            <li class="pb-[10px] text-white">
              <i class="icofont-rounded-right text-[#18d26e]"></i>
              <strong class="text-white">Website:</strong>
              https://github.com/jeydev310
            </li>
            <li class="pb-[10px] text-white">
              <i class="icofont-rounded-right text-[#18d26e]"></i>
              <strong class="text-white">Phone:</strong> +86 182 4255 0239
            </li>
            <li class="pb-[10px] text-white">
              <i class="icofont-rounded-right text-[#18d26e]"></i>
              <strong class="text-white">City:</strong> City : Shenyang,
              LiaoNing, China
            </li>
          </ul>
          <br />
        </div>
        <div class="col-span-1">
          <ul>
            <li class="pb-[10px] text-white">
              <i class="icofont-rounded-right text-[#18d26e]"></i>
              <strong class="text-white">Age:</strong> 31
            </li>
            <li class="pb-[10px] text-white">
              <i class="icofont-rounded-right text-[#18d26e]"></i>
              <strong class="text-white">Degree:</strong> Bachelor
            </li>
            <li class="pb-[10px] text-white">
              <i class="icofont-rounded-right text-[#18d26e]"></i>
              <strong class="text-white">Email:</strong>
              juanjs230@outlook.com
            </li>
            <li class="pb-[10px] text-white">
              <i class="icofont-rounded-right text-[#18d26e]"></i>
              <strong class="text-white">Full time job:</strong>
              Available
            </li>
          </ul>
          <br />
        </div>
      </div>
      <p class="text-white">
        I have worked on many DeFi and Dapps based on several Blockchain
        platform and I have extensive 5+ years of experience in developing and
        writing Smart Contracts for Ethereum, Binance smart chain, Polygon,
        Solana, Avalanche, Fantom Blockchain.
        <br />
        I have also used Web3 to integrate several Smart contracts of different
        blockchain to frontend designs. I have 3+ years of experience using web3
        With several blockchain networks I have developed several Defi and Dapps
        and written 30+ smart contracts including NFT and deployed it in
        blockchain networks.
        <br />
        I am expert in Uniswap, Sushiswap, Pancakeswap, Swapping tokens,
        Staking, Bridge, Yield Farming, Lottery Smart Contracts etc.
        <br />
        I have worked on multiple coding and business start-up projects related
        to blockchains and crypto assets/coins, gaining experience covering
        blockchain, consensus algorithms, Hyperledger, bitcoind, geth, ethminer,
        ethash, ERC20 tokens, JSON RPC, transactions, testnets, on-chain atomic
        swaps, cryptocurrency mining, coin trading, exchanges (both centralized
        and decentralized), and 'crypto ecosystem' modelling. I run my own full
        nodes for BTC, ETH and ETC. I have contributed to multiple whitepapers,
        and been involved in several completed ICOs.
        <br />
        I have developed 20+ Crypto Exchange and ICO Platform and helped several
        clients raise and earn million of dollars worth of Crypto.
        <br />
        I have worked with all the popular blockchains like EOS, Stellar, Waves,
        Ripple, Bitcoin, NEO, Ethereum and Steem etc
        <br />
        <strong>PROFESSIONAL SUMMARY</strong>
        <br />
        ● 10+ years of software development experience in all phases of SDLC
        including Planning, Requirement Analysis, Design, Development, Testing,
        and Deployment
        <br />
        ● 10+ years of experience in front end development using HTML/HTML5,
        XHTML, CSS2/CSS3, JavaScript/Typescript, Bootstrap, jQuery, Ajax, JSON,
        and XML and IDE tools like VSCode, WebStorm, Sublime text, and Eclipse
        <br />
        ● 5 years of experience in back end development in PHP/Laravel and Dot
        Net (C#)
        <br />
        ● 5 years of experience in React, Redux, Redux-Thunk, and Redux-Saga
        <br />
        ● 5 years of experience in Vue.js, VueX, Vuetify.js, Nuxt.js, and
        Element UI Library
        <br />
        ● 5 years of experience in back end development in Node.js/Express/Nest
        <br />● 5 years of experience in developing Restful Web Services and
        Micro Services using Node/Golang
      </p>
    </div>
  </div>
  <!-- CounterVue -->
  <h2
    class="text-[14px] font-medium text-[#aaaaaa] tracking-[2px] after:content-[''] after:w-[120px] after:h-[1px] after:inline-block after:bg-green-600 after:ml-[4px] after:m-[2px] m-[20px] ml-0"
  >
    SKILLS
  </h2>
  <div class="grid grid-cols-12">
    <div
      class="col-span-3 text-white bg-white/[.08] text-center mr-[20px] rounded-[7px] p-[20px] relative mt-[35px]"
    >
      <i
        class="icofont-simple-smile text-[#18d26e] absolute top-[-25px] left-[30%] translate-x-[50%] text-[24px] p-[12px] rounded-[50px] text-[#18d26e] bg-white/[.1]"
      ></i>
      <CounterVue ed="23" index="{1}"></CounterVue>
      <p class="text-[20px] pb-[1rem]">Happy Client</p>
    </div>
    <div
      class="col-span-3 text-white bg-white/[.08] text-center mr-[20px] rounded-[7px] p-[20px] relative mt-[35px]"
    >
      <i
        class="icofont-document-folder text-[#18d26e] absolute top-[-25px] left-[30%] translate-x-[50%] text-[24px] p-[12px] rounded-[50px] text-[#18d26e] bg-white/[.1]"
      ></i>
      <CounterVue ed="42" index="{2}"></CounterVue>
      <p class="text-[20px] pb-[1rem]">Projects</p>
    </div>
    <div
      class="col-span-3 text-white bg-white/[.08] text-center mr-[20px] rounded-[7px] p-[20px] relative mt-[35px]"
    >
      <i
        class="icofont-live-support text-[#18d26e] absolute top-[-25px] left-[30%] translate-x-[50%] text-[24px] p-[12px] rounded-[50px] text-[#18d26e] bg-white/[.1]"
      ></i>
      <CounterVue ed="1463" index="{3}"></CounterVue>
      <p class="text-[20px] pb-[1rem]">Hours of Support</p>
    </div>
    <div
      class="col-span-3 text-white bg-white/[.08] text-center mr-[20px] rounded-[7px] p-[20px] relative mt-[35px]"
    >
      <i
        class="icofont-users-alt-5 text-[#18d26e] absolute top-[-25px] left-[30%] translate-x-[50%] text-[24px] p-[12px] rounded-[50px] text-[#18d26e] bg-white/[.1]"
      ></i>
      <CounterVue ed="3" index="{4}" />
      <p class="text-[20px] pb-[1rem]">Hard Workers</p>
    </div>
  </div>
  <!-- CounterVue -->
  <h2 class="text-[14px] font-medium text-[#aaaaaa] tracking-[2px] after:content-[''] after:w-[120px] after:h-[1px] after:inline-block after:bg-green-600 after:ml-[4px] after:m-[2px] m-[20px] ml-0">
          SKILLS
        </h2>
        <div class="grid grid-cols-12">
          <div class="col-span-6 p-[12px]">

            <SkillVue  :target="100" :title="'REACT JS'" :bgcolor="'#18d26e'" />
            <SkillVue  :target="100" :title="'VUE JS'"   :bgcolor="'#18d26e'" />
            <SkillVue  :target="95" :title="'ANGULAR'"  :bgcolor="'#18d26e'"/>
            <SkillVue  :target="100" :title="'NODE JS'" :bgcolor="'#18d26e'" />
            <SkillVue  :target="100" :title="'PHP'"     :bgcolor="'#18d26e'"/>
            <SkillVue  :target="100" :title="'lARAVEL'"  :bgcolor="'#18d26e'"/>
            <SkillVue  :target="90" :title="'GOLANG'"  :bgcolor="'#18d26e'"/>
            <SkillVue  :target="90" :title="'AWS'"  :bgcolor="'#18d26e'"/>
            <SkillVue  :target="100" :title="'FIGMA'"  :bgcolor="'#18d26e'"/>
          </div>
          <div class="col-span-6 p-[12px]">
   
            <SkillVue :target="100" :title="'REACT NATIVE'"  :bgcolor="'#18d26e'"/>
            <SkillVue :target="80"  :title="'JAVA/KOTLIN'"  :bgcolor="'#18d26e'"/>
            <SkillVue :target="80"  :title="'SWIFT'" :bgcolor="'#18d26e'"/>
            <SkillVue :target="80"  :title="'C#'"  :bgcolor="'#18d26e'"/>
            <SkillVue :target="80"  :title="'QT'"  :bgcolor="'#18d26e'"/>
            <SkillVue :target="100" :title="'MONGODB'"  :bgcolor="'#18d26e'"/>
            <SkillVue :target="90"  :title="'MYSQL'"  :bgcolor="'#18d26e'"/>
            <SkillVue :target="90"  :title="'DOCKER'"  :bgcolor="'#18d26e'"/>
            <SkillVue :target="100" :title="'ADOBE XD'"  :bgcolor="'#18d26e'"/>
          </div>
        </div>

      <!-- <SkillVue  :bgcolor="'#18d26e'" :completed="completed" :title="'REACT JS'"/> -->
</template>
