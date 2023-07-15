<script setup>
import {about} from './../data/nav_prom'
</script>
<template>
	<section>
		<div class="container-fluid">
			<div class="row">
				<div class="col-md-8">
					<img :src="[about.img]" alt="">
				</div>
				<div class="col-md-4">
					<h6 :class="about.color">ABOUT</h6>
					<h1>About Us</h1>
					<p :style="[about.p_front, about.text_color]">
						Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separated they live in Bookmarksgrove right at the coast <br> <br>

						Separated they live in Bookmarksgrove right at the coast of the Semantics, a large language ocean. A small river named Duden flows by their place and supplies it with the necessary regelialia. <br> <br>

						<span><i :class="[about.checkIcon, about.color,about.iconGap]"></i>There live the blind texts</span> <br> <br>
						<span><i :class="[about.checkIcon, about.color,about.iconGap]"></i>Far far away behind the word</span> <br> <br>
						<span><i :class="[about.checkIcon, about.color,about.iconGap]"></i>Their place and supplies</span> <br> <br>
					</p>
					
				</div>
			</div>
		</div>
	</section>
</template>
<style scoped></style>