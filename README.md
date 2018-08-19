Working example is at: http://bruceasmith.com/portfolio/er_counter/

The escape room counter is based on the activity counter exercise from the Lynda.com class ReactJs Essential Training.

I created it as a front-end application, grabbing React and Babel from a content distribution network, with a local fallback, and putting all the components on the index page.  This works great for small projects that don't need server functionality, resulting in a simple, clean project that doesn't have all the extra files you would have if you used create-react-app.

The data for the table is loaded from a JSON object in game_list.js.  I update this list by adding entries to an Excel spreadsheet and then running a VBA routine to generate the JSON file.

Totals and percentages are calculated based on the number of entries in the JSON file combined with the Boolean values for games finished and games won.

Note that the lock is CSS rather than an image.

":^)