<a
	class="flex flex-col items-center gap-2 text-gray-400 uppercase"
	href="https://twitter.com/t3dotgg"
>
	<img src="/theo.jpg" alt="theo" class="rounded-full w-12 h-12" />
	<span>Theo Browne</span>
</a>

<div class="flex flex-col items-center gap-2">
	<span class="text-gray-400">September 6, 2023</span>
	<h1 class="text-4xl font-bold">Turbo 8 is dropping JavaScript</h1>
</div>

<div class="md:max-w-[40rem] text-lg flex flex-col gap-5">
	<p>
		By all accounts, JavaScript has been a big success for web development. I've seen loads of
		people sparkle with joy while working with the dynamic nature of JavaScript, unburdened by the
		constraints of TypeScript's explicit types. But I've never been a fan. Not after giving it five
		minutes, not after giving it five years. So it's with great pleasure that I can announce <a
			href="https://github.com/hotwired/turbo/pull/972">we're dropping JavaScript</a
		> from the next big release of Turbo 8.
	</p>
	<p>
		The fact is that I actually rather dislike JavaScript. I'd go so far as to say it's my
		second-least favorite language after COBOL. Yes, a distant second-least, but a least-favorite
		none the less. This wasn't always the case. But after TypeScript introduced us to the world of
		static types, and all the other improvements that came with it, it's become a real pain to write
		plain JavaScript.
	</p>
	<p>
		I still don't think JavaScript is well-suited for most of the work we do on the client side of
		the web-app equation, but fully respect and appreciate that others feel differently. To me, it's
		simply our misfortune that we still have to work with such an unstructured language, which often
		leads to runtime errors that could have been caught at compile time.
	</p>
	<p>
		JavaScript just gets in the way of that for me. Not just because it lacks strong typing, but
		because it forces us to handle type-related issues at runtime, leading to frustrating debugging
		sessions and unpredictable behavior. Things that should be reliable become fragile, and things
		that should be simple become complex. No thanks!
	</p>
	<p>
		This isn't a plea to convert anyone of anything, though. As I discussed in Programming without
		types, very few programmers are typically interested in giving up strong typing. Most
		programmers find themselves drawn strongly to types or not quite early in their career, and then
		spend the rest of it justifying their choice to themselves and others.
	</p>
	<p>
		That's part of the challenge of this JavaScript vs. TypeScript debate, and full credit to the
		JavaScript enthusiasts for realizing that a full take-over of TypeScript was never going to
		happen, so staying true to the dynamic nature of JavaScript was the way to go. Just because
		Turbo 8 is dropping JavaScript won't mean you can't write your client code in it, or use any
		other library that avoids strong typing. We get to mix and match, which is wonderful.
	</p>
	<p>
		It's also necessary. Because unlike languages like COBOL, which are languages of choice when it
		comes to legacy systems, JavaScript is a language of necessity when it comes to the client side.
		While you may use statically-typed languages that compile to JavaScript, you still have to
		accept the fact that running code in the browser means running JavaScript. So being able to
		write that, free of any type constraints, and free of any strong typing, is a blessing under the
		circumstances.
	</p>
	<p>
		So farewell, JavaScript. May you bring much unpredictability and debugging sessions to your
		tribe while letting the rest of us enjoy TypeScript in the structured and type-safe spirit it
		was originally designed: Embracing strong typing.
	</p>
</div>

<div class="flex flex-col items-center gap-3">
	<span class="uppercase text-gray-400">ABOUT THEO BROWNE</span>
	<span class="text-gray-300">
		Made <a href="https://ping.gg" class="underline">ping.gg</a> for the underdogs as founder and
		CEO of
		<a href="https://t3.gg" class="underline">T3.gg</a>. Created
		<a href="https://create.t3.gg/" class="underline">create-t3-app</a>.
	</span>
	<!-- horizonal line  -->
	<div class="h-0.5 bg-gray-300" />
	<span class="text-gray-300">cloned by <a href="https://twitter.com/uwunetes">embed</a></span>
</div>
