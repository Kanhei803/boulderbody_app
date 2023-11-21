<template>
	<div id="app_style" class="d-flex flex-column justify-content-center mx-auto">
		<div class="sticky_navbar">
			<NavBar />
		</div>
		<div>
			<h1>Home Page</h1>
			<h1>
				Lorem ipsum dolor sit amet consectetur adipisicing elit. Magni, tempore asperiores enim ex maxime nulla laudantium, accusantium explicabo aperiam placeat natus. Consequatur reiciendis, possimus ipsum velit ipsam officia non asperiores. Ipsa, cumque error repellat blanditiis ea dolorem,
				molestias, quis tempore obcaecati enim culpa repellendus illum nemo deleniti consequatur ad a ipsam ex odit optio. Qui autem eaque debitis fugit error? Assumenda voluptas vero sed laborum ab odio, unde quibusdam, rerum ullam quidem qui impedit, excepturi autem possimus sint rem fugiat. Dolor
				doloribus sint harum debitis omnis veritatis repudiandae explicabo accusamus. Dolor cum saepe incidunt necessitatibus hic, iste libero officia iusto quisquam expedita sit. Id molestiae quod dicta ducimus, esse nihil dolor quas iste laborum. At possimus amet ipsum libero aperiam! Delectus
				natus vitae asperiores aliquid culpa consequuntur eius quisquam obcaecati, accusamus eaque excepturi, temporibus magni distinctio cum odit alias iusto inventore fugiat ducimus quis dolores quam, repellendus debitis impedit! Distinctio? Sed voluptates quas illum omnis sapiente quae
				perspiciatis consequuntur perferendis, magni dolor. Aut consectetur tempora omnis odit sunt et explicabo? Modi error cumque, aspernatur possimus ut aut omnis voluptatem doloremque? Commodi qui voluptas, minima possimus, iure neque inventore vel saepe tenetur laudantium nostrum eos hic
				temporibus ratione reiciendis vero fugiat in recusandae similique? Veniam praesentium eum, quidem sapiente sed impedit! Rem, magnam ea eius aliquid atque libero quo in rerum optio, quae corrupti perferendis aspernatur? Impedit, sapiente? Optio aperiam similique est officia excepturi aliquid
				nihil ipsam! Quis libero iste laudantium. Facere obcaecati ipsam repellendus, ex delectus accusamus voluptate nam laboriosam omnis labore molestiae voluptas earum odit rerum magni perspiciatis et similique ducimus culpa quos perferendis reprehenderit distinctio. Vero, porro cum? Quaerat ab
				quidem quis facilis illum inventore laudantium officiis cupiditate, exercitationem mollitia consectetur ratione voluptates architecto quasi et corporis. Natus fugiat sed mollitia, aliquam nisi facilis velit officia distinctio quaerat.
			</h1>
		</div>
	</div>
</template>

<script>
import NavBar from "@/components/NavBar.vue";

export default {
	name: "HomePage",
	components: {
		NavBar,
	},
	data() {
		return {};
	},
	methods: {},
};
</script>

<style scoped>
#app_style {
  max-width: 1300px;
}
.sticky_navbar {
	position: sticky;
	top: 0;
	background-color: rgb(255, 156, 85);
	z-index: 100;
}
</style>
