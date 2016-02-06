# Rows

Stack rows of varying widths down the page.

## CSS

	/* Mobile */

	.row {
	}

	.row-inner {
	   max-width: 900px; /* Define default width */
	   margin: 0 auto; /* Center content */
	   padding: 24px;
	}

	.row-inner > *:last-child {
	   padding-bottom: 0; /* Remove bottom padding from last element for consistent spacing */
	}

	/* Tablet */

	@media screen and (min-width: 768px) {
	   .row-inner {
	      padding:  48px 36px;
	   }
	}

	/* Desktop */

	@media screen and (min-width: 1024px) {
	   .row-inner {
	      padding: 64px 48px;
	   }
	}

## HTML

	<section class="row">
	 <div class="row-inner">
	 </div>
	</section>