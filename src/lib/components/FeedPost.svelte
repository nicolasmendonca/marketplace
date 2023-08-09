<script>
	import FeedPostPublication from './FeedPostPublication.svelte';

	import QuestionForm from './QuestionForm.svelte';

	import Reply from './Reply.svelte';

	import Question from './Question.svelte';
</script>

<section class="group">
	<FeedPostPublication />
	<div class="mx-4 pt-8 space-y-8">
		<div class="space-y-2">
			<Question />
			<Reply />
		</div>
		<div
			class="opacity-0 group-hover:opacity-100 group-focus-within:opacity-100 transition ease-in-out delay-150"
		>
			<QuestionForm />
		</div>
	</div>
</section>
