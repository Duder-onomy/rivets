Binders are the sets of instructions that tell Rivets.js how to update the DOM when a particular model property changes. Rivets.js comes bundled with many commonly-used binders for conveneience, but it is encouraged to extend Rivets.js with your own binders that are specific to your application.

For example, you may be creating a progress bar and need to bind a percentage value to the element's width, or you may be using a third-party library for a toggle switch and would like to use Rivets.js to bind it to model property. For these scenarios, you would create a one-way `width` binder and a two-way `toggle` binder, respectively.