<template>
	<Page>
		<ActionBar>
			<Label text="firebase-ui" />
		</ActionBar>

		<GridLayout>
			<Button class="info" :text="message" />
		</GridLayout>
	</Page>
</template>

<script lang="ts">
import Vue from 'nativescript-vue';
import { DemoSharedFirebaseUi } from '@demo/shared';
import {} from '@nativescript-asharghi/firebase-ui';

export default Vue.extend({
	computed: {
		message() {
			return 'Test firebase-ui';
		},
	},
});
</script>

<style scoped lang="scss">
.info {
	font-size: 20;
	horizontal-align: center;
	vertical-align: center;
}
</style>
