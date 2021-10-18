Rules for contribution.

Fork this repository.

Star this repository.⭐

Choose your favourite programming language.

Add valid program (or code) on that sub repository.

Don't forget to add the problem statement , comments and complexity.⚠️⚠️ It's a must part.

Commit the change and generate a valid pull request.
	) + 'px';
		paddle_1_coord = paddle_1.getBoundingClientRect();
		}
		if (e.key == 's') {
		paddle_1.style.top =
			Math.min(
			board_coord.bottom - paddle_common.height,
			paddle_1_coord.top + window.innerHeight * 0.06
			) + 'px';
		paddle_1_coord = paddle_1.getBoundingClientRect();
		}

		if (e.key == 'ArrowUp') {
		paddle_2.style.top =
			Math.max(
			board_coord.top,
			paddle_2_coord.top - window.innerHeight * 0.1
			) + 'px';
		paddle_2_coord = paddle_2.getBoundingClientRect();
		}
		if (e.key == 'ArrowDown') {
After carefully reviewing your code , if it is valid then it will be merged otherwise discarded.
