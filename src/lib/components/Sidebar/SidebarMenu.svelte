<script>
	import { File, FileFilled, Folder, Image } from '$lib/icons';
</script>

<ul class="menu menu-xs w-full max-w-xs overflow-hidden rounded-lg bg-base-200">
	<li>
		<a href={null} class="truncate">
			<span class="text-primary">
				<FileFilled />
			</span>
			<span>resume.pdf</span>
		</a>
	</li>
	<li>
		<details>
			<summary class="truncate">
				<span class="text-primary">
					<Folder />
				</span>
				My Files
			</summary>
			<ul>
				<li>
					<a href={null}>
						<File />
						Project-final.psd
					</a>
				</li>
				<li>
					<a href={null}>
						<File />
						Project-final-2.psd
					</a>
				</li>
				<li>
					<details>
						<summary>
							<Folder />
							Images
						</summary>
						<ul>
							<li>
								<a href={null}>
									<Image />
									Screenshot1.png
								</a>
							</li>
							<li>
								<a href={null}>
									<Image />
									Screenshot2.png
								</a>
							</li>
							<li>
								<details open>
									<summary>
										<Folder />
										Others
									</summary>
									<ul>
										<li>
											<a href={null}>
												<Image />
												Screenshot3.png
											</a>
										</li>
									</ul>
								</details>
							</li>
						</ul>
					</details>
				</li>
			</ul>
		</details>
	</li>
	<li>
		<a href={null} class="truncate">
			<span class="text-primary">
				<FileFilled />
			</span>
			reports-final-2.pdf
		</a>
	</li>
</ul>
