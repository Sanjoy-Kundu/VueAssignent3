<script setup>
import {colors} from './../data/nav_prom'
import {digitalService} from './../data/nav_prom'

</script>
<template>
	<section class="mt-5">
		<div class="container pt-5">
			<div class="row mt-5">
			<div class="col-5">
				<h6 :class="digitalService.color">DIGITAL SERVICES</h6>
				<h1 :style="digitalService.frontWeight">Selling Digital <br> Services</h1>
				<p :style="[colors.p_front, colors.text_color]">Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separated they live in Bookmarksgrove right at the coast</p>
				<p>
					<span :style="[colors.p_front, colors.text_color]"><i :class="[digitalService.checkIcon, digitalService.color]"></i>There live the blind texts</span> <br> <br>

					<span :style="[colors.p_front, colors.text_color]"><i :class="[digitalService.checkIcon, digitalService.color]"></i>Far far away behind the word</span>
				</p>


				<q><span :style="[colors.p_front, digitalService.textStyle]">Separated they live in Bookmarksgrove right at the coast of the Semantics, a large language ocean. A small river named Duden flows by their place and supplies it with the necessary regelialia. </span></q>

				<div class="pt-5 d-flex align-self-center">
					<img :src="digitalService.profileImg" alt="" :style="digitalService.profileImageStyle">
					<div class="ms-2">
						<h6>{{ digitalService.profileName }}</h6>
						<h6 :style="colors.text_color">{{digitalService.title }}</h6>
					</div>
				</div>
			</div>
			<div class="col-7">
				<img :src="digitalService.image" alt="" :class="[digitalService.imageWidth]">
			</div>
		</div>
		</div>
	</section>
</template>
<style scoped>

</style>