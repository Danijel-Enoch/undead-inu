<script>
	import banner from '../assets/herobanner.jpg'
	import phone from '../assets/adPhone.jpg';
	import phone1 from '../assets/phone.jpeg';
	import skull from '../assets/skull4.png';
	import skull5 from '../assets/skull5.png';
	import phone2 from '../assets/phone2.jpeg';
	import telegram from '../assets/icons8-telegram-app-96.png';
	import twitter from '../assets/icons8-twitter-96.png';
	import blue from '../assets/blue-skull.jpg';
    import zombie from '../assets/zombie4.png'
</script>

<div class="bg-blue-500 h-94 testfont">
	<div class="p-0">
       <h1 class="text-center  font-extrabold  text-shadow-xl text-9xl  py-10 ">
        UnDead-Inu
       </h1>  
    </div>
	<div class="flex flex-col rounded-sm m-32">
		<img class="rounded-t-3xl" src={banner} alt="" />

		<div class=" bg-white flex lg:flex-row md:flex-col">
			<div class="w-96 lg:ml-10 md:ml-14 carousel">
				<div id="slide1" class="relative w-full pt-6 carousel-item">
					<img src={phone1} class="w-full" />
					<div
						class="absolute flex justify-between transform -translate-y-1/2 left-5 right-5 top-1/2"
					>
						<a href="/#slide2" class="btn btn-circle">❮</a>
						<a href="/#slide2" class="btn btn-circle">❯</a>
					</div>
				</div>
				<div id="slide2" class="relative w-full pt-20 carousel-item">
					<img src={phone2} class="w-full" />
					<div
						class="absolute flex justify-between transform -translate-y-1/2 left-5 right-5 top-1/2"
					>
						<a href="/#slide1" class="btn btn-circle">❮</a>
						<a href="/#slide1" class="btn btn-circle">❯</a>
					</div>
				</div>
			</div>
			<p class=" w-1/2 text-3xl font-bold  text-center lg:mt-56 md:mt-10 pt-2 md:ml-32">
				The Undead are rising and are coming to the Ethereum Blockchain. It’s the year 2022, the
				zombies are here and predicted to wipe out all apes from planet earth.
			</p>
		</div>

		<div class="flex felx-row pl-24 bg-white">
			<p class="ml-24  text-center text-shadow-lg text-6xl font-bold mt-24">
				THE APOCALYPSE IS HERE
			</p>
			<img class=" w-96" src={skull} alt="" />
		</div>
		<div class="bg-white items-center flex flex-col">
			<p class=" h-1/2 font-bold  text-4xl text-center ">
				Undead Inu is an horror inspired meme and deflationary <br /> token on the ethereum blockchain
				with a 12% tax on every onchain transaction.
			</p>
			<span class=" font-bold text-4xl text-shadow-lg animate-bounce mb-10"
				><br /> 5% Marketing <br /> 5% Development <br /> 2% Auto - Liquidity
			</span>
		</div>

		<div class="bg-blue-100 ">
			<div class="flex flex-row  items-center ml-96  ">
				<img src={telegram} alt="" />
				<img src={twitter} alt="" />
			</div>
		</div>

		<div class="  bg-[url('src/assets/earth.jpg')] flex flex-row gap-3">
			<div class=" bg-black text-white text-center px-10 py-10 my-20 ml-10">
				<span class="font-bold text-3xl"> UTILITY </span>
				<p class="text-2xl">
					Undead Inu isn’t just an horror meme token, but a utility token with its upcoming NFTs,
					Staking and P2E gaming platform - THe UnDeaD.
				</p>
			</div>
			<div class=" bg-black text-white text-center px-10 py-10 my-20">
				<span class="font-bold text-3xl"> UNIQUE MEME APPROACH </span>
				<p class="text-2xl">
					Undead Inu stands out from all of the hybrid inu which are mostly dog, anime or cat
					inspired this kicking off new trend to the meme ecosystem
				</p>
			</div>
			<div class=" bg-black text-white text-center  py-10 px-10 my-20">
				<span class="font-bold text-3xl"> MARKETING AND PROMOTIONs </span>
				<p class="text-2xl">
					With outlined strategic prelaunch post launch marketing plus a team with experience, the
					sky’s only the limit for $DEAD.
				</p>
			</div>
			<div class=" bg-black text-white text-center  py-10 px-10 my-20 mr-10">
				<span class="font-bold text-3xl"> UPCOMING STAKING, NFTS and P2E PLATFORM </span>
				<p class="text-2xl">
					Onboarded an experienced developement team of 7 people to work on each of the outlined
					tech milestones.
				</p>
			</div>
		</div>

		<div class="item-center bg-blue-500 py-20 px-20 flex flex-row">
			<button class=" border-black font-bold text-2xl border-4 p-10 ml-80 rounded-full text-black">
				<img class="w-32" src={skull5} alt="" />
				BUY $DEAD
			</button>
		</div>

		<div class=" flex flex-col gap-12 bg-white pl-0 text-center rounded-2xl pb-20">
			<h1 class="text-9xl font-bold text-shadow-xl pl-0 text-center pt-10 ">Tokenomics</h1>
			<h2 class="font-bold text-4xl ">
				Total Supply:
				<span class="text-6xl text-shadow-xl">1,000,000,000</span>
				$DEAD
			</h2>
			<h2 class="font-bold text-4xl">
				MORGUE ( DEAD ADDRESS): <span class="text-6xl text-shadow-xl">45%</span> <br />
				LIQUIDITY: <span class="text-6xl text-shadow-xl">50%</span> <br />
				PRE-LAUNCH MARKETING: <span class="text-6xl text-shadow-xl">5%</span> ,<br />
			</h2>
			<h2 class="font-bold text-4xl">
				INITIAL LIQUIDITY: <span class="text-6xl text-shadow-xl"> 10ETH </span>
			</h2>
		</div>

		<h2 class="text-center font-extrabold text-black text-8xl pt-10  text-shadow-xl">ROADMAP</h2>
		<div class="flex flex-row gap-7 py-10 pl-24 ">
			<div
				class="carousel-item shadow-xl gap-2 flex flex-col text-4xl font-bold text-center p-10 bg-black rounded-3xl w-52 text-white text-shadow-xl"
			>
				<h1>PHASE</h1>
				<h2 class="text-6xl">1</h2>
				<p>
					- Pre- Launch Marketing Campaigns <br />
					- $DEAD Uniswap Listing <br />
					- CG and CMC Application and Listings <br />
					- Community Incentive Program ( Meme Contest and Giveaways) <br />
				</p>
			</div>
			<div
				class="carousel-item shadow-xl gap-2 flex flex-col text-4xl font-bold text-center p-10 bg-black rounded-3xl w-52 text-white text-shadow-xl"
			>
				<h1>PHASE</h1>
				<h2 class="text-6xl">2</h2>
				<p>
					- NFT Ecosystem Launch <br />
					- Staking Integration <br />
					- P2E App Beta Launch <br />
					- Buyback and Burn Event <br />
					- Increased Utility. <br />
				</p>
			</div>
			<div
				class="carousel-item shadow-xl gap-2 flex flex-col text-4xl font-bold text-center p-10 bg-black rounded-3xl w-52 text-white text-shadow-xl"
			>
				<h1>PHASE</h1>
				<h2 class="text-6xl">3</h2>
				<p>
					<br />
					-Partnerships and Increased Development <br />
					- CEX Listings <br />
					- P2E Game Full Version Launch ( Web, iOS and Android) <br />
				</p>
			</div>
		</div>

		<div class="bg-white rounded-3xl font-bold gap-2 p-10 flex-col flex">
			<span class="text-center text-4xl mx-10 pl-62 text-shadow-xl py-10"> HOW TO BUY </span>
            <span class="pl-80">
                Follow these simple steps to buy the $DEAD token.
            </span>
			<ul class="steps steps-vertical text-2xl font-minecraft">
				<li class="step ">
					Create a Wallet through either Metamask or TrustWallet Both of these Wallets have
					Android/iOS apps, but MetaMask also has a Google Chrome Extension
				</li>

				<li class="step  ">
					Purchase ETH ( Ethereum) Buy Ethereum coin with crypto through your chosen wallet
					application or via traditional centralized exchanges like Coinbase, Kraken or Binance
				</li>
				<li class="step">
					Nagivate the Uniswap website via your selected browser. Click “ Connect “ in the Top Right
					Corner of the page to connect your wallet to Uniswap. Once your $ETH balance has loaded
					in, click “ Select a Token” and enter the $DEAD contract address: (Will be announced upon
					launch)
                    <br>
                    ....
				</li>
				<li class="step">
					<br />
					Before Swapping, Adjust your Slippage Click on the toolbox icon, and set your slippage to 13%.
					You might encounter a warning “ Your transaction may be frontrun”. This % may vary during the
					day, based on how much volume there currently is. You basically always want the lowest % where
					it gives the warning.
				</li>
				<li class="step">
					<br />
					Confirm the Swap Enter the desired amount of $DEAD, hit “swap”, and confirm the transaction
					in your wallet.
				</li>
			</ul>
            <img class="w-40"  src={zombie} alt="">
		</div>
	</div>
	<div class="bg-black text-white font-bold w-full font-li text-center testfont">
		Disclaimer: The information provided on this website does not constitute investment advice or
		financial advice and shouldn’t be treated as such!
	</div>
</div>

<style>
    @font-face {
  font-family: "minecraft";
  src: url("../fonts/zombie.ttf")
}
@font-face {
  font-family: "test";
  src: url("../fonts/PopulationZeroBB.otf")
}

.testfont{
    font-family:"minecraft";
}
</style>