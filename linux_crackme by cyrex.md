<!-- wp:paragraph -->
<p><a href="https://crackmes.one/crackme/5ab77f5633c5d40ad448c2d6" target="_blank" rel="noreferrer noopener">https://crackmes.one/crackme/5ab77f5633c5d40ad448c2d6</a></p>
<!-- /wp:paragraph -->

<!-- wp:image {"id":6902,"sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large"><img src="https://persecure.files.wordpress.com/2022/10/image-433.png?w=1021" alt="" class="wp-image-6902"/></figure>
<!-- /wp:image -->

<!-- wp:separator -->
<hr class="wp-block-separator has-alpha-channel-opacity"/>
<!-- /wp:separator -->

<!-- wp:paragraph {"align":"center","backgroundColor":"pale-cyan-blue","fontSize":"medium"} -->
<p class="has-text-align-center has-pale-cyan-blue-background-color has-background has-medium-font-size"><strong>Determine the file type</strong></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"fontSize":"medium"} -->
<p class="has-medium-font-size">Use the <strong><em>file</em></strong> command to determine the file type.</p>
<!-- /wp:paragraph -->

<!-- wp:image {"id":6906,"sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large"><img src="https://persecure.files.wordpress.com/2022/10/image-436.png?w=724" alt="" class="wp-image-6906"/></figure>
<!-- /wp:image -->

<!-- wp:separator -->
<hr class="wp-block-separator has-alpha-channel-opacity"/>
<!-- /wp:separator -->

<!-- wp:paragraph {"align":"center","backgroundColor":"pale-cyan-blue","fontSize":"medium"} -->
<p class="has-text-align-center has-pale-cyan-blue-background-color has-background has-medium-font-size"><strong><em>Test the program</em></strong></p>
<!-- /wp:paragraph -->

<!-- wp:image {"id":6908,"sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large"><img src="https://persecure.files.wordpress.com/2022/10/image-437.png?w=636" alt="" class="wp-image-6908"/></figure>
<!-- /wp:image -->

<!-- wp:separator -->
<hr class="wp-block-separator has-alpha-channel-opacity"/>
<!-- /wp:separator -->

<!-- wp:paragraph {"align":"center","backgroundColor":"pale-cyan-blue","fontSize":"medium"} -->
<p class="has-text-align-center has-pale-cyan-blue-background-color has-background has-medium-font-size"><strong>Strings</strong></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"fontSize":"medium"} -->
<p class="has-medium-font-size">Use <strong><em>strings</em></strong> to print the sequences of printable characters in files.</p>
<!-- /wp:paragraph -->

<!-- wp:image {"id":6909,"sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large"><img src="https://persecure.files.wordpress.com/2022/10/image-438.png?w=667" alt="" class="wp-image-6909"/><figcaption class="wp-element-caption">Password can be found with strings.</figcaption></figure>
<!-- /wp:image -->

<!-- wp:separator -->
<hr class="wp-block-separator has-alpha-channel-opacity"/>
<!-- /wp:separator -->

<!-- wp:paragraph {"align":"center","backgroundColor":"pale-cyan-blue","fontSize":"medium"} -->
<p class="has-text-align-center has-pale-cyan-blue-background-color has-background has-medium-font-size"><strong>Analyze</strong></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"fontSize":"medium"} -->
<p class="has-medium-font-size"><em>Dissemble the program </em>in GDB</p>
<!-- /wp:paragraph -->

<!-- wp:image {"id":6904,"sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large"><img src="https://persecure.files.wordpress.com/2022/10/image-435.png?w=546" alt="" class="wp-image-6904"/></figure>
<!-- /wp:image -->

<!-- wp:paragraph -->
<p>The program will get an input and use strcmp to check and the jne instruction next.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>The password is stored in [ebp-0x20] and moved to eax at +82. Which we can see the ASCII text in GDB peda. </p>
<!-- /wp:paragraph -->

<!-- wp:image {"id":6903,"sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large"><img src="https://persecure.files.wordpress.com/2022/10/image-434.png?w=1024" alt="" class="wp-image-6903"/></figure>
<!-- /wp:image -->

<!-- wp:separator -->
<hr class="wp-block-separator has-alpha-channel-opacity"/>
<!-- /wp:separator -->

<!-- wp:paragraph {"align":"center","backgroundColor":"cyan-bluish-gray","fontSize":"small"} -->
<p class="has-text-align-center has-cyan-bluish-gray-background-color has-background has-small-font-size"><strong>Test the program </strong></p>
<!-- /wp:paragraph -->

<!-- wp:image {"id":6911,"sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large"><img src="https://persecure.files.wordpress.com/2022/10/image-439.png?w=653" alt="" class="wp-image-6911"/></figure>
<!-- /wp:image -->
