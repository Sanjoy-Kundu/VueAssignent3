<script setup>
	const img = 'https://preview.colorlib.com/theme/launch/images/market-launch-pana.svg'
    import { colors } from '../data/nav_prom'


</script>
<template>
	<section>
		<div class="container">
			<div class="row mt-5">
				<div class="col-6 pt-5">
					<h1 :style="colors.promth1">Promote Your <br/>Products by <br/>Colorlib</h1>
					<p :style="[colors.text_color, colors.padding, colors.p_front]">Another cool free html css template by <a href="" :style="[colors.p_color, colors.underlineNone]">Colorlib</a> Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separated they live in Bookmarksgrove right at the coast</p>
					<button :class="[colors.primaryButton, colors.roundedPillBorder]">see features</button>
					<button :class="[colors.pricingHover, colors.roundedPillBorder,colors.buttonGap]">Pricing</button>
				</div>
				<div class="col-6">
					<img :src="img" alt="" class="img-fluid">
				</div>
			</div>
		</div>
	</section>
</template>
<style scoped></style>