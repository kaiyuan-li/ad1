<template>
	<div class='contextmenu'>
		<ul>
			<li v-for="item in menuItems">
				{{item.content}}
			</li>
		</ul>
	</div>
</template>

<script>
export default {
  name: 'ContextMenu',
  data () {
    return {
      menuItems: [
        {content: 'foo'},
        {content: 'bar'}
      ]
    }
  }
}
</script>

<style scoped>
  .contextmenu {
	left: 20px;
    width: 200px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-between;
    border-radius: 1em;
    background: #0f0;
    overflow: hidden;
    box-shadow: 0 0 5px rgba(25,25,25,.25);
  }
</style>
