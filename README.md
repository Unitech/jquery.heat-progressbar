# jquery.heat-progressbar

[Follow Me on Twitter](https://twitter.com/strzel_a)

## Image 

![Heat-example](https://github.com/Alexandre-Strzelewicz/jquery.heat-progressbar/blob/master/heat-example.png)

## Options

### Default values

		val : Math.floor(Math.random()*100),  # Value to pass, must be between 0-100 
                                                      # else random values are used
		displayText : true,                   # Display value inside progressbar
		animate : true,                       # Animate progress bar ?
		delayMs : 120,                        # Delay to expand progress (only if animated)
		caractersToAdd : '',                  # Caracters to add after value displayed
		valueCss : ''                         # Add here CSS to customize value
		
## Example

Example :

    <div style="200px" id="heat-indicator"></div>
    
    $('#heat-indicator').heatcolor({
                                               value : 50, 
                                               displayText : true,
                                               caractersToAdd : '°F',
				               valueCss : 'font-weight : bold; color : white;'
				});
							    
							    
