<template>
<h1>Pure Decentralized Application</h1>
<div class="normal">
  The fuzz word DApp (<b>D</b>ecentralized <b>A</b>pplication) is usually used to describe the blockchain applications whose core logic resides in smart contracts. Smart contracts are usually opensourced, peer-reviewed and audited, and they run on unstoppable anti-censorship blockchains. Thus DApps are much more decentralized than close-source softwares running on servers owned by a single company.<br/>
  However, applications are far more than smart contracts. They absolutely need user interfaces, which are web pages deployed at specific domains. These web pages interact with smart contracts through wallets such as MetaMask, and also interact with some backend server for historical and statistical informations and optimum choices. For example, UniSwap needs backend server to draw candlestick charts and to compute optimum path in swapping two types of assets.<br/>
  These frontend/backend stuffs make current DApps not so decentralized. Actually they are just semi-DApps because there are so many possibilities of single-point failure: DNS problems, website crashing, censorship of the backend server, etc.<br/>
  Pure Decentralized Applications (Pure DApps) are a kind of blockchain applications which avoid the centralization problems of frontend/backend. They have the following features:<br/>
  <ol>
  <li>The frontend is opensourced and free to be deployed at any domain, or on IPFS.</li>
  <li>The backend is not needed, or is opensourced to allow anybody deploy it at anywhere.</li>
  </ol>
  Some of the famous projects on Ethereum are Pure DApps, such as <a href="https://github.com/gnosis/safe-react">Gnosis-Safe</a> and <a href="https://github.com/ensdomains/ens-app">ENS</a>, whose frontend code and contract code are both opensource.<br/>
  Pure DApps are encouraged (but not required) in smartBCH's ecosystem. Its first pure dapp is the explorer smartscan.cash. Unlike the other blockchain explorers, smartscan.cash does not need a specific backend to work. It provides services by just connecting to a full-node client of smartBCH.<br/>
  This website aims to boost Pure DApps' development and adoption on smartBCH. More information will be provided soon.
   
</div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'App',
})
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.normal {
   width: 1000px;
   margin: auto;
   text-align: left;
   font-size: 24px;
}
</style>
