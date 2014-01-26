WREKtranet is WREK's intranet system that provides online tools for our DJs to use to manage music, staff, concert tickets, and more. It was started about a decade ago in PHP2 and hasn't seen significant cleanup or modernization since.

For my senior design course, I worked with [Kyle Petrovich](http://kpetrovi.ch) and other peers to start a new base for WREKtranet in [Ruby on Rails](http://rubyonrails.org) and improve the usability and implementation of older features.

<figure>
    <a class="media-image" href="/images/wrektranet/1.png">
       <img src="/images/wrektranet/1.png" alt="WREK's contest book." />
    </a>
    <figcaption>
        A list of concert tickets to be given out as contests to listeners.
    </figcaption>
</figure>

The new platform also includes [AngularJS](http://angularjs.org) as a client-side framework to make it easier to develop single-page interactive tools, and uses [Bootstrap](http://getbootstrap.com) with simple design guidelines.

<figure class="media-image-medium">
    <a class="media-image" href="/images/wrektranet/2.png">
       <img src="/images/wrektranet/2.png" alt="Front page" />
    </a>
    <figcaption>
        A simple and quick contest signup page for staff to use to receive show tickets.
    </figcaption>
</figure>

The site was organized into three primary functions to address the lack of organization in the old system: tools that DJs use on air, general staff tools, and administrative/management tools.

<figure class="media-image-medium media-reverse">
    <a class="media-image" href="/images/wrektranet/3.png">
       <img src="/images/wrektranet/3.png" alt="Front page" />
    </a>
    <figcaption>
        A sample contest page designed for on-air readability.
    </figcaption>
</figure>