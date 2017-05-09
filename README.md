ACF flexible content 

<?php

if( have_rows('flexible_content_field_name') ): while ( have_rows('flexible_content_field_name') ) : the_row();


        if( get_row_layout() == 'SectionId' ): ?>
		
		<!-- section content here -->

       <?php elseif( get_row_layout() == 'SectionId' ): ?>

		<!-- section content here -->

       <?php elseif( get_row_layout() == 'SectionId' ): ?>

		<!-- section content here -->
		
<?php endif; endwhile; endif; ?>
