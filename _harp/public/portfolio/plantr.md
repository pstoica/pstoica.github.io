Plantr was a project for Georgia Tech's _Mobile Applications and Services for Converged Networks_ made with [Kyle Petrovich](http://kpetrovi.ch), Ying Yao, and [Casey Mann](http://caseymann.com).

<figure class="media-image-medium">
    <a class="media-image" href="/images/plantr/1.png">
       <img src="/images/plantr/1.png" alt="Plant list and status overview." />
    </a>
    <figcaption>
    	<p>Plant lists are provided for each garden a user belongs to. Color-coded icons help display general health.</p>

    	<p>The app was prototyped using [Ruby on Rails](http://rubyonrails.org) and [jQuery Mobile](http://jquerymobile.com/).</p>
    </figcaption>
</figure>

A wireless Arduino device was created with moisture and light sensors, sending updates to a computer or base station at a variable interval. Each plant is attached to a unique sensor identifier. The server keeps track of the logs it receives, and stats are available as charts.

Using the [Twilio](http://twilio.com) API, we implemented a group SMS system to be used for each garden. The server messages the group when plants need watering or if they're doing well again, preventing people from overwatering plants.

<figure class="media-reverse media-image-medium">
    <a class="media-image" href="/images/plantr/2.png">
       <img src="/images/plantr/2.png" alt="Plant page and stat charts." />
    </a>
    <figcaption>
    	<p>A sample plant status page, charting sunlight and moisture over time alongside current readings.</p>

    	<p>Users can also add tasks for plants (e.g. trimming) with configurable SMS reminders.</p>
    </figcaption>
</figure>