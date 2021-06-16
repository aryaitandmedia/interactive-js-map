https://www.fiverr.com/futurist_amit/place-an-interactive-js-map-into-any-website

# arya-interactive-js-map
Interactive JS Map for website

# USAGE
Create an Object Instance

	<script src="jquery-1.8.2.min.js"></script>
	<script type="text/javascript">
		var map = new IntMap();
	</script>

# Default Options
    {
		'header_text' : 'AIT&M - Interactive JS Map',
    	'company_name' : 'Your Company',
		'company_logo' : 'images/your_company_logo.png', 
		'company_logo_alt' : 'Your Company Around the World.',
		'append_to' : 'body',
		'style' : '',
		'continent' : {
			'europe' : {
				'title' : 'Western Europe',
				'description' : 'Spain, UK, Finland, Sweden, Malta, Denmark, Belgium, Switzerland, Iceland, France, Germany, Austria, Italy, Norway, Holland, Ireland, Portugal, Andorra, Luxembourg, Estonia, Latvia, Lithuania, Czech Republic, Slovakia, Poland, Hungary, Bulgaria, Slovenia.',
			},
			'africa' : {
				'title' : 'Africa and Middle East',
				'description' : 'Pakistan, Egypt, Iran, South Africa, Ghana, Israel, Saudi Arabia, Ivory Coast, Angola, Algeria, Qatar, UAE, Nigeria, Yemen, Kuwait, Iraq, Togo, Senegal, Sudan, Kenya, Baherin, Ethiopia, Morocco, Libya, Niger, Mali, Cameroon, Gabon, Burkina Faso, Mozambique, Oman.',
			},
			'asia': {
				'title' : 'Asia and Oceania',
				'description' : 'India, Nepal, Thailand, Vietnam, Singapore, Malaysia, Maldives, the Philippines, Indonesia, Brunei, Japan, Korea South China, Myanmar, Australia, New Zealand, France Polynesia, Papua New Guinea, Taiwan, Bangladesh, Hong Kong.',
			},
			'east-europe': {
				'title' : 'Eastern Europe',
				'description' : 'Russia, Ukraine, Moldova, Kazakhstan, Belarus, Armenia, Azerbaijan.',
			},
			'south-america': {
				'title' : 'Central &amp; South America',
				'description' : 'Brazil, Mexico, Puerto Rico, Guatemala, Uruguay, Republic Dominican Republic, El Salvador, Chile, Colombia, Argentina, Panama, Venezuela, Honduras, Bolivia, Peru, Ecuador, Paraguay, Costa Rica, I. Falkland Islands, French Guiana, Guadalupe.',
			},
			'north-america': {
				'title' : 'North America',
				'description' : 'USA, Canada.',
			},
		}
	}


# Override Options
	 var map = new IntMap({
		    'header_text' : 'Your Header',
		    'company_logo' : 'your_logo_path/your_logo.png', 
		    'company_logo_alt' : 'Your Company Around the World.',
		    'company_name' : 'Your Company',
		    'append_to' : 'body',
		    'style' : '',
		    'continent' : {
		       'europe' : {
			  'title' : 'Western Europe',
			  'description' : 'Test',
		       },
		       'africa' : {
			  'title' : 'Africa and Middle East',
			  'description' : 'Test2',
		       },
		       'asia': {
			  'title' : 'Asia and Oceania',
			  'description' : 'Test3',
		       },
		       'east-europe': {
			  'title' : 'Eastern Europe',
			  'description' : 'Test4',
		       },
		       'south-america': {
			  'title' : 'Central &amp; South America',
			  'description' : 'Test5',
		       },
		       'north-america': {
			  'title' : 'North America',
			  'description' : 'Test6',
		       }
		    }
		 })

 # Override Options : 'style'
            # You can directly add styles as string or as an object key value pair
            
            # As a string
            'style' : 'h3 {color:red;}',
            
            # As an object key value pair
            'style' : {
               'header': {
               'background' : '#000',
               'htag' : '#fff',
               'font-family' : 'san-serif',
               },
               'map': {
               'background' : '#222',
               'htag' : 'blue',
               'ptag' : 'red',
               'font_h2' : 'san-serif',
               'font_p' : 'san-serif',
               }
            },
	    

        
