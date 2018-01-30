## Buttons

#### Colors
We worked over the original Bootstrap classes, choosing a different, slightly intenser color pallete:

<button class="btn btn-default">Default</button>
<button class="btn btn-primary">Primary</button>
<button class="btn btn-info">Info</button>
<button class="btn btn-success">Success</button>
<br>
<button class="btn btn-warning">Warning</button>
<button class="btn btn-danger">Danger</button>
<button class="btn btn-neutral">Neutral</button>

    <button class="btn btn-default">Default</button>
    <button class="btn btn-primary">Primary</button>
    <button class="btn btn-info">Info</button>
    <button class="btn btn-success">Success</button>
    <button class="btn btn-warning">Warning</button>
    <button class="btn btn-danger">Danger</button>
    <button class="btn btn-neutral">Neutral</button>

#### Sizes
Buttons come in all needed sizes:

<button class="btn btn-primary btn-lg">Large</button>
<button class="btn btn-primary">Normal</button>
<button class="btn btn-primary btn-sm">Small</button>

    <button class="btn btn-primary btn-lg">Large</button>
    <button class="btn btn-primary">Normal</button>
    <button class="btn btn-primary btn-sm">Small</button>

#### Styles
We added extra classes that can help you better customise the look. You can use regular buttons, rounded corners buttons or plain simple buttons. Let's see some examples:

<button class="btn btn-primary">Default</button>
<button class="btn btn-primary btn-round">Round</button>
<button class="btn btn-primary btn-round">
	<i class="now-ui-icons ui-2_favourite-286"></i> With Icon
</button>
<button class="btn btn-primary btn-icon  btn-icon-mini btn-round">
	<i class="now-ui-icons ui-2_favourite-28"></i>
</button>
<button class="btn btn-primary btn-simple">Simple</button>

    <button class="btn btn-primary">Default</button>
    <button class="btn btn-primary btn-round">Round</button>
    <button class="btn btn-primary btn-round">
    	<i class="now-ui-icons ui-2_favourite-286"></i> With Icon
    </button>
    <button class="btn btn-primary btn-icon  btn-icon-mini btn-round">
    	<i class="now-ui-icons ui-2_favourite-28"></i>
    </button>
    <button class="btn btn-primary btn-simple">Simple</button>

Button groups and disabled state all work like they are supposed to. We used the Nucleo icons that can be found [here](https://nucleoapp.com/?ref=creativetim).

</br>
## Checkboxes
To use the custom checkboxes, you don't need to import any separate Javascript file, just add the below code:

<div class="form-check">
	<label class="form-check-label">
		<input class="form-check-input" type="checkbox">
		<span class="form-check-sign"></span>
		Unchecked
	</label>
</div>

<div class="form-check">
	<label class="form-check-label">
		<input class="form-check-input" type="checkbox">
		<span class="form-check-sign"></span>
		Checked
	</label>
</div>


<div class="form-check disabled">
	<label class="form-check-label">
		<input class="form-check-input" type="checkbox" disabled>
		<span class="form-check-sign"></span>
		Disabled Unchecked
	</label>
</div>

<div class="form-check disabled">
	<label class="form-check-label">
		<input class="form-check-input" type="checkbox" checked disabled>
		<span class="form-check-sign"></span>
		Disabled Checked
	</label>
</div>

    <div class="form-check">
    	<label class="form-check-label">
    		<input class="form-check-input" type="checkbox">
    		<span class="form-check-sign"></span>
    		Unchecked
    	</label>
    </div>

    <div class="form-check">
    	<label class="form-check-label">
    		<input class="form-check-input" type="checkbox">
    		<span class="form-check-sign"></span>
    		Checked
    	</label>
    </div>


    <div class="form-check disabled">
    	<label class="form-check-label">
    		<input class="form-check-input" type="checkbox" disabled>
    		<span class="form-check-sign"></span>
    		Disabled Unchecked
    	</label>
    </div>

    <div class="form-check disabled">
    	<label class="form-check-label">
    		<input class="form-check-input" type="checkbox" checked disabled>
    		<span class="form-check-sign"></span>
    		Disabled Checked
    	</label>
    </div>

</br>
## Radio Buttons
To use the custom radio buttons, you don't need to import any separate Javascript file, just add the below code:

<div class="form-check form-check-radio">
	<label class="form-check-label">
		<input class="form-check-input" type="radio" name="exampleRadios" id="exampleRadios1" value="option1">
		<span class="form-check-sign"></span>
		Radio is off
	</label>
</div>

<div class="form-check form-check-radio">
	<label class="form-check-label">
		<input class="form-check-input" type="radio" name="exampleRadios" id="exampleRadios1" value="option2" checked="">
		<span class="form-check-sign"></span>
		Radio is on
	</label>
</div>

<div class="form-check form-check-radio disabled">
	<label class="form-check-label">
		<input class="form-check-input" type="radio" name="exampleRadios1" id="exampleRadios2" value="option3" disabled="">
		<span class="form-check-sign"></span>
	 	Disabled radio is off
	</label>
</div>

<div class="form-check form-check-radio disabled">
   <label class="form-check-label">
	   <input class="form-check-input" type="radio" name="exampleRadios1" id="exampleRadios2" value="option4" disabled="" checked="">
	   <span class="form-check-sign"></span>
	   Disabled radio is on
   </label>
</div>

    <div class="form-check form-check-radio">
        <label class="form-check-label">
            <input class="form-check-input" type="radio" name="exampleRadios" id="exampleRadios1" value="option1">
            <span class="form-check-sign"></span>
            Radio is off
        </label>
    </div>

    <div class="form-check form-check-radio">
        <label class="form-check-label">
            <input class="form-check-input" type="radio" name="exampleRadios" id="exampleRadios1" value="option2" checked="">
            <span class="form-check-sign"></span>
            Radio is on
        </label>
    </div>

    <div class="form-check form-check-radio disabled">
        <label class="form-check-label">
            <input class="form-check-input" type="radio" name="exampleRadios1" id="exampleRadios2" value="option3" disabled="">
            <span class="form-check-sign"></span>
            Disabled radio is off
        </label>
    </div>

    <div class="form-check form-check-radio disabled">
       <label class="form-check-label">
           <input class="form-check-input" type="radio" name="exampleRadios1" id="exampleRadios2" value="option4" disabled="" checked="">
           <span class="form-check-sign"></span>
           Disabled radio is on
       </label>
    </div>

</br>
## Toggle Buttons
If you want to use something more special than a checkbox, we recomment the toggle buttons.

<input type="checkbox" name="checkbox" class="bootstrap-switch" checked/>

<input type="checkbox" name="checkbox" class="bootstrap-switch"
      data-on-label="ON"
      data-off-label="OFF"
/>

</br>
## Dropdown
We are very proud to present the dropdown which has a subtle animation. We also thought of another use-case: dropdown with flags.

<div class="row">
<div class="col-md-3">
<div class="dropdown">
    <a href="#pablo" class="btn btn-default dropdown-toggle" data-toggle="dropdown" id="navbarDropdownMenuLink1">
    	Regular
    </a>
    <ul class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink1">
        <a class="dropdown-item" href="#">Action</a>
        <a class="dropdown-item" href="#">Another action</a>
        <a class="dropdown-item" href="#">Something else here</a>
        <div class="dropdown-divider"></div>
        <a class="dropdown-item" href="#">Separated link</a>
        <div class="dropdown-divider"></div>
        <a class="dropdown-item" href="#">One more separated link</a>
    </ul>
</div>
</div>

<div class="col-md-3">
<div class="dropdown">
    <a href="#" class="btn btn-default dropdown-toggle " data-toggle="dropdown" id="navbarDropdownMenuLink2">
        <img src="img/flags/US.png"> Flags
    </a>
    <ul class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink2">
        <li>
            <a class="dropdown-item" href="#">
                <img src="img/flags/DE.png"> Deutsch</a>
        </li>
        <li>
            <a class="dropdown-item" href="#">
                <img src="img/flags/GB.png"> English(UK)</a>
        </li>
        <li>
            <a class="dropdown-item" href="#">
                <img src="img/flags/FR.png"> Français</a>
        </li>
        <li>
            <a class="dropdown-item" href="#">
                <img src="img/flags/RO.png"> Română</a>
        </li>
        <li>
            <a class="dropdown-item" href="#">
                <img src="img/flags/IT.png"> Italiano</a>
        </li>
        <li class="divider"></li>
        <li>
            <a class="dropdown-item" href="#">
                <img src="img/flags/ES.png"> Español
                <span class="label label-default">soon</span>
            </a>
        </li>
        <li>
            <a class="dropdown-item" href="#">
                <img src="img/flags/BR.png"> Português
                <span class="label label-default">soon</span>
            </a>
        </li>
        <li>
            <a class="dropdown-item" href="#">
                <img src="img/flags/JP.png"> 日本語
                <span class="label label-default">soon</span>
            </a>
        </li>
    </ul>
</div>
</div>
</div>

    <div class="dropdown">
        <a href="#pablo" class="btn btn-default dropdown-toggle" data-toggle="dropdown" id="navbarDropdownMenuLink1">
            Regular
        </a>
        <ul class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink1">
            <a class="dropdown-item" href="#">Action</a>
            <a class="dropdown-item" href="#">Another action</a>
            <a class="dropdown-item" href="#">Something else here</a>
            <div class="dropdown-divider"></div>
            <a class="dropdown-item" href="#">Separated link</a>
            <div class="dropdown-divider"></div>
            <a class="dropdown-item" href="#">One more separated link</a>
        </ul>
    </div>

</br>
## Inputs
We restyled the Bootstrap input to give it a more flat, minimal look. You can use them with regular labels, states or input groups.

<div class="row">
<div class="col-md-4">
	<div class="form-group">
		<input type="text" value="" placeholder="Regular" class="form-control">
	</div>
</div>

<div class="col-md-4">
	<div class="form-group has-success">
		<input type="text" value="Success" class="form-control form-control-success">
	</div>
</div>

<div class="col-md-4">
	<div class="form-group has-danger">
		<input type="email" value="Error Input" class="form-control form-control-danger">
	</div>
</div>

<div class="col-md-4">
	<div class="input-group">
		<span class="input-group-addon">
			<i class="fa fa-user-circle"></i>
		</span>
		<input type="text" class="form-control" placeholder="Left Font Awesome Icon">
	</div>
</div>

<div class="col-md-4">
	<div class="input-group">
		<input type="text" class="form-control" placeholder="Right Nucleo Icon">
		<span class="input-group-addon">
			<i class="now-ui-icons users_single-02"></i>
		</span>
	</div>
</div>
</div>

    <div class="form-group">
        <input type="text" value="" placeholder="Regular" class="form-control">
    </div>

    <div class="form-group has-success">
		<input type="text" value="Success" class="form-control form-control-success">
	</div>

    <div class="form-group has-danger">
		<input type="email" value="Error Input" class="form-control form-control-danger">
	</div>

    <div class="input-group">
		<span class="input-group-addon">
			<i class="fa fa-user-circle"></i>
		</span>
		<input type="text" class="form-control" placeholder="Left Font Awesome Icon">
	</div>

    <div class="input-group">
		<input type="text" class="form-control" placeholder="Right Nucleo Icon">
		<span class="input-group-addon">
			<i class="now-ui-icons users_single-02"></i>
		</span>
	</div>

</br>
## Textarea
The textarea has a new style, so it looks similar to all other inputs.

<textarea class="form-control" placeholder="Here can be your nice text" rows="5"></textarea>

    <textarea class="form-control" placeholder="Here can be your nice text" rows="5"></textarea>

</br>
## Select Bootstrap **v1.12.2**
We have styled the select picker to look similar to the dropdown and the other inputs. To see the original documentation, please check out Silvio Moreto repo on [GitHub](http://silviomoreto.github.io/bootstrap-select/).

<div class="row">
    <div class="col-md-4">
    <select class="selectpicker" data-size="7" data-style="btn btn-primary btn-round" title="Single Select">
        <option disabled selected>Single Option</option>
        <option value="2">Foobar</option>
        <option value="3">Is great</option>
    </select>
    </div>
</div>


    <select class="selectpicker" data-size="7" data-style="btn btn-primary btn-round" title="Single Select">
        <option disabled selected>Single Option</option>
        <option value="2">Foobar</option>
        <option value="3">Is great</option>
    </select>

</br>
## FileUpload Jasny **v3.1.3**
We have styled the select picker to look similar to the dropdown and the other inputs.

For more information please check [Full Github Documentation](http://www.jasny.net/bootstrap/).

<h4><small>Regular Image</small></h4>
<div class="fileinput fileinput-new text-center" data-provides="fileinput">
    <div class="fileinput-new thumbnail img-raised">
        <img src="img/image_placeholder.jpg" alt="...">
    </div>
    <div class="fileinput-preview fileinput-exists thumbnail img-raised"></div>
    <div>
        <span class="btn btn-raised btn-round btn-default btn-file">
            <span class="fileinput-new">Select image</span>
            <span class="fileinput-exists">Change</span>
            <input type="file" name="...">
        </span>
        <a href="#pablo" class="btn btn-danger btn-round fileinput-exists" data-dismiss="fileinput"><i class="now-ui-icons ui-1_simple-remove"></i> Remove</a>
    </div>
</div>

<h4><small>Avatar</small></h4>
<div class="fileinput fileinput-new text-center" data-provides="fileinput">
    <div class="fileinput-new thumbnail img-circle img-raised">
        <img src="img/placeholder.jpg" alt="...">
    </div>
    <div class="fileinput-preview fileinput-exists thumbnail img-circle img-raised"></div>
    <div>
        <span class="btn btn-raised btn-round btn-default btn-file">
            <span class="fileinput-new">Add Photo</span>
            <span class="fileinput-exists">Change</span>
            <input type="file" name="..."></span>
        <br>
        <a href="#pablo" class="btn btn-danger btn-round fileinput-exists" data-dismiss="fileinput"><i class="now-ui-icons ui-1_simple-remove"></i> Remove</a>
    </div>
</div>

    <div class="fileinput fileinput-new text-center" data-provides="fileinput">
        <div class="fileinput-new thumbnail img-raised">
            <img src="assets/img/image_placeholder.jpg" alt="...">
        </div>
        <div class="fileinput-preview fileinput-exists thumbnail img-raised"></div>
        <div>
            <span class="btn btn-raised btn-round btn-default btn-file">
                <span class="fileinput-new">Select image</span>
                <span class="fileinput-exists">Change</span>
                <input type="file" name="...">
            </span>
            <a href="#pablo" class="btn btn-danger btn-round fileinput-exists" data-dismiss="fileinput"><i class="now-ui-icons ui-1_simple-remove"></i> Remove</a>
        </div>
    </div>

</br>
## Parallax
The parallax scrolling effect can be activated by simple putting `data-parallax="true"` , like in the below code. If you want to deactivate parallax, you have to change `true` value with `false`.

    <div class="page-header clear-filter" filter-color="orange">
        <div class="page-header-image" data-parallax="true" style="background-image: url('./assets/img/header.jpg');">
        </div>

        {{ content }}
    </div>


</br>
## Navbar
The classic Bootstrap Navbar was restyled:

<nav class="navbar navbar-expand-lg bg-white">
    <div class="container">
        <div class="navbar-translate">
            <a class="navbar-brand" href="#pablo">
               Navbar
            </a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navigation" aria-controls="navigation-index" aria-expanded="false" aria-label="Toggle navigation">
       	        <span class="navbar-toggler-bar bar1"></span>
    	        <span class="navbar-toggler-bar bar2"></span>
    	        <span class="navbar-toggler-bar bar3"></span>
 	        </button>

        </div>

        <div class="collapse navbar-collapse" id="navigation">
    	    <ul class="navbar-nav">
                <li class="nav-item active">
                    <a class="nav-link" href="#pablo">
                        Home
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#pablo">Link</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link disabled" href="#pablo">Disabled</a>
                </li>
            </ul>
        </div>
    </div>
</nav>

    <nav class="navbar navbar-expand-lg bg-white">
        <div class="container">
            <div class="navbar-translate">
                <a class="navbar-brand" href="#pablo">
        	        Navbar
        	    </a>
                <button class="navbar-toggler" type="button" data-toggle="collapse" aria-controls="navigation-index" aria-expanded="false" aria-label="Toggle navigation">
           	        <span class="navbar-toggler-bar bar1"></span>
        	        <span class="navbar-toggler-bar bar2"></span>
        	        <span class="navbar-toggler-bar bar3"></span>
     	        </button>    
            </div>

            <div class="collapse navbar-collapse">
        	    <ul class="navbar-nav">
                    <li class="nav-item active">
                        <a class="nav-link" href="#pablo">
                            Home
                        </a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#pablo">Link</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link disabled" href="#pablo">Disabled</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

Besides the white navbar, we added 5 new colors: grey, blue, green, yellow, red. If you want to use one of them, you have to replace the .bg-white with the class for the chosen color `.bg-info`, `.bg-success`, `.bg-warning`, `.bg-danger`, `.bg-default`.

<nav class="navbar navbar-expand-lg bg-info">
    <div class="container">
        <div class="navbar-translate">
            <a class="navbar-brand" href="#pablo">
                Navbar
            </a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" aria-controls="navigation-index" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-bar bar1"></span>
                <span class="navbar-toggler-bar bar2"></span>
                <span class="navbar-toggler-bar bar3"></span>
            </button>
        </div>

        <div class="collapse navbar-collapse">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item active">
                    <a class="nav-link" href="#pablo">
                        Home
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#pablo">Link</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link disabled" href="#pablo">Disabled</a>
                </li>
            </ul>
        </div>
    </div>
</nav>

<nav class="navbar navbar-expand-lg bg-success">
    <div class="container">
        <div class="navbar-translate">
            <a class="navbar-brand" href="#pablo">
                Navbar
            </a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" aria-controls="navigation-index" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-bar bar1"></span>
                <span class="navbar-toggler-bar bar2"></span>
                <span class="navbar-toggler-bar bar3"></span>
            </button>
        </div>

        <div class="collapse navbar-collapse">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item active">
                    <a class="nav-link" href="#pablo">
                        Home
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#pablo">Link</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link disabled" href="#pablo">Disabled</a>
                </li>
            </ul>
        </div>
    </div>
</nav>

<nav class="navbar navbar-expand-lg bg-warning">
    <div class="container">
        <div class="navbar-translate">
            <a class="navbar-brand" href="#pablo">
                Navbar
            </a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" aria-controls="navigation-index" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-bar bar1"></span>
                <span class="navbar-toggler-bar bar2"></span>
                <span class="navbar-toggler-bar bar3"></span>
            </button>
        </div>

        <div class="collapse navbar-collapse">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item active">
                    <a class="nav-link" href="#pablo">
                        Home
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#pablo">Link</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link disabled" href="#pablo">Disabled</a>
                </li>
            </ul>
        </div>
    </div>
</nav>

<nav class="navbar navbar-expand-lg bg-danger">
    <div class="container">
        <div class="navbar-translate">
            <a class="navbar-brand" href="#pablo">
                Navbar
            </a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" aria-controls="navigation-index" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-bar bar1"></span>
                <span class="navbar-toggler-bar bar2"></span>
                <span class="navbar-toggler-bar bar3"></span>
            </button>
        </div>

        <div class="collapse navbar-collapse">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item active">
                    <a class="nav-link" href="#pablo">
                        Home
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#pablo">Link</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link disabled" href="#pablo">Disabled</a>
                </li>
            </ul>
        </div>
    </div>
</nav>

<nav class="navbar navbar-expand-lg bg-default">
    <div class="container">
        <div class="navbar-translate">
            <a class="navbar-brand" href="#pablo">
                Navbar
            </a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" aria-controls="navigation-index" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-bar bar1"></span>
                <span class="navbar-toggler-bar bar2"></span>
                <span class="navbar-toggler-bar bar3"></span>
            </button>
        </div>

        <div class="collapse navbar-collapse">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item active">
                    <a class="nav-link" href="#pablo">
                        Home
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#pablo">Link</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link disabled" href="#pablo">Disabled</a>
                </li>
            </ul>
        </div>
    </div>
</nav>

Besides all this customisation, we have an extra navbar. .navbar-transparent is a special class that you can to use if you want the navbar to be transparent and then turn to color after scrolling the attribute `color-on-scroll="500"`, where 500 is the number of pixels that you need to scroll till the navbar is coloring. We recommend that the part of your page that has the transparent navbar contains something non-cluttered, like an image. If you want to see a nice example in details, check the [Profile Page](http://demos.creative-tim.com/now-ui-kit/examples/profile-page.html).

</br>
## Nav Pills
We changed the design for the Bootstrap nav pills into something a bit more fresh. We also added more color classes for customisation like `.nav-pills-primary`, `.nav-pills-info`, `.nav-pills-success`, `.nav-pills-warning`, `.nav-pills-danger`.

<p>**Simple**</p>
We added coloured shadows to the pills and created two options: horizontal and vertical.

<div class="row">
<div class="col-md-6">
<ul class="nav nav-pills nav-pills-primary" role="tablist">
    <li class="nav-item">
        <a class="nav-link active" data-toggle="tab" href="#link1" role="tablist">
            Profile
        </a>
    </li>
    <li class="nav-item">
        <a class="nav-link" data-toggle="tab" href="#link2" role="tablist">
            Settings
        </a>
    </li>
    <li class="nav-item">
        <a class="nav-link" data-toggle="tab" href="#link3" role="tablist">
            Options
        </a>
    </li>
</ul>
</div>

<div class="col-md-4">
<ul class="nav nav-pills nav-pills-primary flex-column" role="tablist">
  	<li class="nav-item">
		<a class="nav-link active" data-toggle="tab" href="#link4" role="tablist">
			Profile
		</a>
  	</li>
  	<li class="nav-item">
		<a class="nav-link" data-toggle="tab" href="#link5" role="tablist">
			Settings
		</a>
  	</li>
  	<li class="nav-item">
		<a class="nav-link" data-toggle="tab" href="#link6" role="tablist">
			Options
		</a>
  	</li>
</ul>
</div>
</div>

<p>**With Icons**</p>
If you want to also add icons, you can use this version with the two options: horizontal and vertical. To use them, please add the `.nav-pills-icons` class.

<div class="row">
<div class="col-md-6">
<ul class="nav nav-pills nav-pills-primary nav-pills-icons" role="tablist">
	<li class="nav-item">
		<a class="nav-link active" data-toggle="tab" href="#link7" role="tablist">
			<i class="now-ui-icons objects_umbrella-13"></i>
			Home
		</a>
	</li>
	<li class="nav-item">
		<a class="nav-link" data-toggle="tab" href="#link8" role="tablist">
			<i class="now-ui-icons shopping_shop"></i>
			Messages
		</a>
	</li>
	<li class="nav-item">
		<a class="nav-link" data-toggle="tab" href="#link9" role="tablist">
			<i class="now-ui-icons ui-2_settings-90"></i>
			Settings
		</a>
	</li>
</ul>
</div>

<div class="col-md-3">
<ul class="nav nav-pills nav-pills-primary nav-pills-icons flex-column" role="tablist">
	<li class="nav-item">
		<a class="nav-link active" data-toggle="tab" href="#link10" role="tablist">
			<i class="now-ui-icons objects_umbrella-13"></i>
			Home
		</a>
	</li>
	<li class="nav-item">
		<a class="nav-link" data-toggle="tab" href="#link11" role="tablist">
			<i class="now-ui-icons ui-2_settings-90"></i>
			Settings
		</a>
	</li>
</ul>
</div>
</div>

<p>**Only Icons**</p>
If you want to also add only icons, you can use this version with the two options: horizontal and vertical. To use them, please add the `.nav-pills-just-icons` class.

<ul class="nav nav-pills nav-pills-primary nav-pills-just-icons" role="tablist">
    <li class="nav-item">
        <a class="nav-link" data-toggle="tab" href="#profile" role="tablist">
            <i class="now-ui-icons design_image"></i>
        </a>
    </li>
    <li class="nav-item">
        <a class="nav-link active" data-toggle="tab" href="#home" role="tablist">
            <i class="now-ui-icons location_world"></i>
        </a>
    </li>
    <li class="nav-item">
        <a class="nav-link" data-toggle="tab" href="#messages" role="tablist">
            <i class="now-ui-icons sport_user-run"></i>
        </a>
    </li>
</ul>



</br>
## Pagination
The Bootstrap pagination elements were customised to fit the overall theme. Besides the classic look, we also added the color classes to offer more customisation like `.pagination-info`, `.pagination-success`, `.pagination-warning`, `.pagination-danger`, `.pagination-primary`.

<div class="row">
<div class="col-md-4">
    <ul class="pagination pagination-primary">
        <li class="page-item">
            <a class="page-link" href="#link" aria-label="Previous">
    		    <span aria-hidden="true"><i class="fa fa-angle-double-left" aria-hidden="true"></i></span>
    		</a>
        </li>
        <li class="page-item active"><a class="page-link" href="#">1</a></li>
        <li class="page-item"><a class="page-link" href="#">2</a></li>
        <li class="page-item"><a class="page-link" href="#">3</a></li>
        <li class="page-item"><a class="page-link" href="#">4</a></li>
        <li class="page-item">
			<a class="page-link" href="#link" aria-label="Next">
				<span aria-hidden="true"><i class="fa fa-angle-double-right" aria-hidden="true"></i></span>
			</a>
		</li>
    </ul>
</div>

<div class="col-md-4">
    <ul class="pagination pagination-info">
        <li class="page-item active"><a class="page-link" href="#">1</a></li>
        <li class="page-item"><a class="page-link" href="#">2</a></li>
        <li class="page-item"><a class="page-link" href="#">3</a></li>
        <li class="page-item"><a class="page-link" href="#">4</a></li>
    </ul>
</div>

<div class="col-md-4">
    <ul class="pagination pagination-warning">
        <li class="page-item active"><a class="page-link" href="#">1</a></li>
        <li class="page-item"><a class="page-link" href="#">2</a></li>
        <li class="page-item"><a class="page-link" href="#">3</a></li>
        <li class="page-item"><a class="page-link" href="#">4</a></li>
    </ul>
</div>

<div class="col-md-4">
    <ul class="pagination pagination-success">
        <li class="page-item">
            <a class="page-link" href="#link" aria-label="Previous">
                <span aria-hidden="true"><i class="fa fa-angle-double-left" aria-hidden="true"></i></span>
            </a>
        </li>
        <li class="page-item active"><a class="page-link" href="#">1</a></li>
        <li class="page-item"><a class="page-link" href="#">2</a></li>
        <li class="page-item"><a class="page-link" href="#">3</a></li>
        <li class="page-item"><a class="page-link" href="#">4</a></li>
        <li class="page-item">
			<a class="page-link" href="#link" aria-label="Next">
				<span aria-hidden="true"><i class="fa fa-angle-double-right" aria-hidden="true"></i></span>
			</a>
		</li>
    </ul>
</div>

<div class="col-md-4">
    <ul class="pagination pagination-danger">
        <li class="page-item active"><a class="page-link" href="#">1</a></li>
        <li class="page-item"><a class="page-link" href="#">2</a></li>
        <li class="page-item"><a class="page-link" href="#">3</a></li>
        <li class="page-item"><a class="page-link" href="#">4</a></li>
    </ul>
</div>

<div class="col-md-4">
    <ul class="pagination">
        <li class="page-item active"><a class="page-link" href="#">1</a></li>
        <li class="page-item"><a class="page-link" href="#">2</a></li>
        <li class="page-item"><a class="page-link" href="#">3</a></li>
        <li class="page-item"><a class="page-link" href="#">4</a></li>
    </ul>
</div>
</div>

We build two classes `.arrow-margin-left` and `.arrow-margin-right`, so once that you will apply these classes pagination will be full-width. To see where to put the mentioned classes please see the example below.

<div class="pagination-container justify-content-center">
    <ul class="pagination pagination-primary">
        <li class="page-item arrow-margin-left">
            <a class="page-link" href="#" aria-label="Previous">
                <span aria-hidden="true"><i class="fa fa-angle-double-left" aria-hidden="true"></i></span>
            </a>
        </li>
        <li class="page-item">
            <a class="page-link" href="#">1</a>
        </li>
        <li class="page-item">
            <a class="page-link" href="#">2</a>
        </li>
        <li class="page-item active">
            <a class="page-link" href="#">3</a>
        </li>
        <li class="page-item">
            <a class="page-link" href="#">4</a>
        </li>
        <li class="page-item">
            <a class="page-link" href="#">5</a>
        </li>
        <li class="page-item arrow-margin-right">
            <a class="page-link" href="#" aria-label="Next">
                <span aria-hidden="true"><i class="fa fa-angle-double-right" aria-hidden="true"></i></span>
            </a>
        </li>
    </ul>
</div>

    //Pagination simple
    <ul class="pagination pagination-primary">
      <li class="page-item active"><a class="page-link" href="#">1</a></li>
      <li class="page-item"><a class="page-link" href="#">2</a></li>
      <li class="page-item"><a class="page-link" href="#">3</a></li>
      <li class="page-item"><a class="page-link" href="#">4</a></li>
      <li class="page-item"><a class="page-link" href="#">5</a></li>
    </ul>


    //Pagination full-width
    <div class="pagination-container justify-content-center">
        <ul class="pagination pagination-primary">
            <li class="page-item arrow-margin-left">
                <a class="page-link" href="#" aria-label="Previous">
                    <span aria-hidden="true"><i class="fa fa-angle-double-left" aria-hidden="true"></i></span>
                </a>
            </li>


            <li class="page-item"><a class="page-link" href="#">1</a></li>
            <li class="page-item"><a class="page-link" href="#">2</a></li>
            <li class="page-item active"><a class="page-link" href="#">3</a></li>
            <li class="page-item"><a class="page-link" href="#">4</a></li>
            <li class="page-item"><a class="page-link" href="#">5</a></li>



            <li class="page-item arrow-margin-right">
                <a class="page-link" href="#" aria-label="Next">
                    <span aria-hidden="true"><i class="fa fa-angle-double-right" aria-hidden="true"></i></span>
                </a>
            </li>
        </ul>
    </div>

</br>
## Progress Bar
The progress bars from Bootstrap hold the same classes and functionality. Adding this kit over your existing project will only make it look more clean. The default line is gray, each bar has a specific color but you can add some colors for the background lines using the next classes `.progress-primary`, `.progress-info`, `.progress-success`, `.progress-warning`, `.progress-danger`.

<div class="progress-container">
    <span class="progress-badge">Default</span>
    <div class="progress">
        <div class="progress-bar" role="progressbar" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100" style="width: 25%;">
            <span class="progress-value">25%</span>
        </div>
    </div>
</div>

<div class="progress-container progress-primary">
    <span class="progress-badge">Primary</span>
    <div class="progress">
        <div class="progress-bar progress-bar-warning" role="progressbar" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100" style="width: 60%;">
            <span class="progress-value">60%</span>
        </div>
    </div>
</div>

<div class="progress-container progress-info">
    <span class="progress-badge">Info</span>
    <div class="progress">
        <div class="progress-bar progress-bar-warning" role="progressbar" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100" style="width: 60%;">
            <span class="progress-value">60%</span>
        </div>
    </div>
</div>

<div class="progress-container progress-success">
    <span class="progress-badge">Success</span>
    <div class="progress">
        <div class="progress-bar progress-bar-warning" role="progressbar" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100" style="width: 60%;">
            <span class="progress-value">60%</span>
        </div>
    </div>
</div>

<div class="progress-container progress-danger">
    <span class="progress-badge">Danger</span>
    <div class="progress">
        <div class="progress-bar progress-bar-warning" role="progressbar" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100" style="width: 60%;">
            <span class="progress-value">60%</span>
        </div>
    </div>
</div>

<div class="progress-container progress-warning">
    <span class="progress-badge">Warning</span>
    <div class="progress">
        <div class="progress-bar progress-bar-warning" role="progressbar" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100" style="width: 60%;">
            <span class="progress-value">60%</span>
        </div>
    </div>
</div>

    <div class="progress-container">
        <span class="progress-badge">Default</span>
        <div class="progress">
            <div class="progress-bar" role="progressbar" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100" style="width: 25%;">
                <span class="progress-value">25%</span>
            </div>
        </div>
    </div>

    <div class="progress-container progress-primary">
        <span class="progress-badge">Primary</span>
        <div class="progress">
            <div class="progress-bar progress-bar-warning" role="progressbar" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100" style="width: 60%;">
                <span class="progress-value">60%</span>
            </div>
        </div>
    </div>

    <div class="progress-container progress-info">
        <span class="progress-badge">Info</span>
        <div class="progress">
            <div class="progress-bar progress-bar-warning" role="progressbar" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100" style="width: 60%;">
                <span class="progress-value">60%</span>
            </div>
        </div>
    </div>

    <div class="progress-container progress-success">
        <span class="progress-badge">Success</span>
        <div class="progress">
            <div class="progress-bar progress-bar-warning" role="progressbar" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100" style="width: 60%;">
                <span class="progress-value">60%</span>
            </div>
        </div>
    </div>

    <div class="progress-container progress-danger">
        <span class="progress-badge">Danger</span>
        <div class="progress">
            <div class="progress-bar progress-bar-warning" role="progressbar" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100" style="width: 60%;">
                <span class="progress-value">60%</span>
            </div>
        </div>
    </div>

    <div class="progress-container progress-warning">
        <span class="progress-badge">Warning</span>
        <div class="progress">
            <div class="progress-bar progress-bar-warning" role="progressbar" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100" style="width: 60%;">
                <span class="progress-value">60%</span>
            </div>
        </div>
    </div>

</br>
## Sliders **v9.1.0**
We restyled noUIslider, while keeping the design consistent. You can use other classes for colors like `.slider-info`, `.slider-success`, `.slider-warning`, `.slider-danger`, `.slider-primary`. Check also [noUISlider Full Documentation](https://refreshless.com/nouislider/).

<div id="sliderRegular" class="slider"></div>
</br>
<div id="sliderDouble" class="slider slider-primary"></div>





    <!-- Markup -->
    <div id="sliderRegular" class="slider"></div>
    <div id="sliderDouble" class="slider slider-primary"></div>

    <!-- Javascript -->
    $('#sliderRegular').noUiSlider({
    	start: 40,
    	connect: "lower",
    	range: {
    	    min: 0,
    	    max: 100
    	}
    });

    $('#sliderDouble').noUiSlider({
    	start: [20, 60] ,
    	connect: true,
    	range: {
    	    min: 0,
    	    max: 100
    	}
    });

</br>
## How to setup Google API Keys
1.Go to https://developers.google.com/maps/documentation/javascript/get-api-key

2.Scroll to the “Get an API key” Title and press the “Get a Key” Button

3.Choose a name for your project then press on Create and Enable API

4.Get the Key and place it in your project where is this script:

    <script type="text/javascript" src="https://maps.googleapis.com/maps/api/js?key=YOUR_KEY_HERE"></script>

</br>
## Labels
We restyled the default options for labels and we added the filled class, that can be used in any combination.

<span class="badge badge-default">Default</span>
<span class="badge badge-primary">Primary</span>
<span class="badge badge-success">Success</span>
<span class="badge badge-info">Info</span>
<span class="badge badge-warning">Warning</span>
<span class="badge badge-danger">Danger</span>
<span class="badge badge-neutral">Neutral</span>

    <span class="badge badge-default">Default</span>
    <span class="badge badge-primary">Primary</span>
    <span class="badge badge-success">Success</span>
    <span class="badge badge-info">Info</span>
    <span class="badge badge-warning">Warning</span>
    <span class="badge badge-danger">Danger</span>
    <span class="badge badge-neutral">Neutral</span>

</br>
## Nucleo Icons
Through most of the examples in this kit, we have used 100 Nucleo Icons for the Now Ui Kit. View all the [example icons](http://demos.creative-tim.com/now-ui-kit/nucleo-icons.html). If you want more than 2100 icons please check the official [Nucleo Icons Pack](https://nucleoapp.com/?ref=creativetim).

<i class="now-ui-icons users_single-02"></i>

    <i class="now-ui-icons users_single-02"></i>

</br>
## Bootstrap Datetimepicker **v4.17.47**
We have created the design of the date-time picker made by [Eonasdan](https://github.com/Eonasdan). We have changed the colors, typography and buttons. You can choose from 5 different colors: `orange`, `blue`, `green`, `red`, `yellow`. To activate the color for datetimepicker you must put the attribute `data-color` with the desired color like in example below.

For more information please check [Full Github Documentation](https://eonasdan.github.io/bootstrap-datetimepicker/).

Here is a coded example:

<div class="row">
<div class="col-md-4">
    <p>Datetimepicker Default</p>
    <input type="text" class="form-control datetimepicker" value="10/05/2016">
</div>

<div class="col-md-4">
    <p>Datetimepicker Primary</p>
    <input type="text" class="form-control datetimepicker" value="10/05/2016" data-color="orange">
</div>
</div>

    <!-- markup -->
    <input type="text" class="form-control datetimepicker" value="10/05/2016">
    <input type="text" class="form-control datetimepicker" value="10/05/2016" data-color="orange">

    <!-- javascript -->

    if($(".datetimepicker").length != 0){
        $('.datetimepicker').datetimepicker({
            icons: {
                time: "now-ui-icons tech_watch-time",
                date: "now-ui-icons ui-1_calendar-60",
                up: "fa fa-chevron-up",
                down: "fa fa-chevron-down",
                previous: 'now-ui-icons arrows-1_minimal-left',
                next: 'now-ui-icons arrows-1_minimal-right',
                today: 'fa fa-screenshot',
                clear: 'fa fa-trash',
                close: 'fa fa-remove'
            }
        });

        $('.datepicker').datetimepicker({
            format: 'MM/DD/YYYY',
            icons: {
                time: "now-ui-icons tech_watch-time",
                date: "now-ui-icons ui-1_calendar-60",
                up: "fa fa-chevron-up",
                down: "fa fa-chevron-down",
                previous: 'now-ui-icons arrows-1_minimal-left',
                next: 'now-ui-icons arrows-1_minimal-right',
                today: 'fa fa-screenshot',
                clear: 'fa fa-trash',
                close: 'fa fa-remove'
           }
        });

        $('.timepicker').datetimepicker({
            format: 'H:mm',    // use this format if you want the 24hours timepicker
            format: 'h:mm A',    //use this format if you want the 12hours timpiecker with AM/PM toggle
            icons: {
                time: "now-ui-icons tech_watch-time",
                date: "now-ui-icons ui-1_calendar-60",
                up: "fa fa-chevron-up",
                down: "fa fa-chevron-down",
                previous: 'now-ui-icons arrows-1_minimal-left',
                next: 'now-ui-icons arrows-1_minimal-right',
                today: 'fa fa-screenshot',
                clear: 'fa fa-trash',
                close: 'fa fa-remove'
            }
        });
    };

## Modals
We restyled the classic Bootstrap Modal and gave it a more simple look.
<!-- Button trigger modal -->
<button class="btn btn-primary" data-toggle="modal" data-target="#myModal">
  Launch demo modal
</button>

<div class="modal fade show" id="myModal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
	<div class="modal-dialog">
		<div class="modal-content">
			<div class="modal-header justify-content-center">
				<button type="button" class="close" data-dismiss="modal" aria-hidden="true">
					<i class="now-ui-icons ui-1_simple-remove"></i>
				</button>
				<h4 class="title title-up">Modal title</h4>
			</div>
			<div class="modal-body">
				<p>Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separated they live in Bookmarksgrove right at the coast of the Semantics, a large language ocean. A small river named Duden flows by their place and supplies it with the necessary regelialia. It is a paradisematic country, in which roasted parts of sentences fly into your mouth.
				</p>
			</div>
			<div class="modal-footer">
				<button type="button" class="btn btn-default">Nice Button</button>
				<button type="button" class="btn btn-danger" data-dismiss="modal">Close</button>
			</div>
		</div>
	</div>
</div>

    <!-- Button trigger modal -->
    <button class="btn btn-primary" data-toggle="modal" data-target="#myModal">
      Launch demo modal
    </button>

    <!-- Modal Core -->
    <div class="modal fade" id="myModal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
      <div class="modal-dialog">
        <div class="modal-content">
          <div class="modal-header">
            <button type="button" class="close" data-dismiss="modal" aria-hidden="true">&times;</button>
            <h4 class="modal-title" id="myModalLabel">Modal title</h4>
          </div>
          <div class="modal-body">
            Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separated they live in Bookmarksgrove right at the coast of the Semantics, a large language ocean. A small river named Duden flows by their place and supplies it with the necessary regelialia. It is a paradisematic country, in which roasted parts of sentences fly into your mouth. Even the all-powerful Pointing has no control about the blind texts it is an almost unorthographic life One day however a small line of blind text by the name of Lorem Ipsum decided to leave for the far World of Grammar.
          </div>
          <div class="modal-footer">
            <button type="button" class="btn btn-default btn-simple" data-dismiss="modal">Close</button>
            <button type="button" class="btn btn-info btn-simple">Save</button>
          </div>
        </div>
      </div>
    </div>

</br>
## Tooltips
We restyled the Bootstrap tooltip.

<button type="button" class="btn btn-default" data-toggle="tooltip" data-placement="right" title="Tooltip on right" id="nume">Button with Tooltip</button>

    <!-- Markup -->
    <button type="button" class="btn btn-default" data-toggle="tooltip" data-placement="right" title="Tooltip on right">Button with Tooltip</button>

    <!-- Javascript -->
    $('[data-toggle="tooltip"]').tooltip();

</br>
## Popovers
We restyled the Bootstrap popover to align with the Now Ui Kit Concept. You have the option to set color of the background changing the value of attribute `data-color=""` with one of the next values: `popover-info`, `popover-warning`, `popover-danger`, `popover-success`.
See the following example:

<button type="button" class="btn btn-default" data-container="body" data-original-title="Popover On Right" data-toggle="popover" data-placement="right" data-content="Here will be some very useful information about his popover." data-color="primary">
    Button with popover
</button>

    <!-- markup -->
    <button type="button" class="btn btn-default" data-toggle="popover" data-placement="right" title="Popover on top" data-content="Here will be some very useful information about his popover.">On top</button>


    <!-- javascript -->
    $('[data-toggle="popover"]').popover();

</br>
## Notifications
The new notifications are looking fresh and clean. They go great with the navbar. For these notifications examples we used the `.container-fluid` class, so they will be fluid, please use the class `.container` when you use them outside of the `.wrapper` so they will be alignd with the general page container.

<div class="alert alert-success" role="alert">
	<div class="container">
		<div class="alert-icon">
			<i class="now-ui-icons ui-2_like"></i>
		</div>
		<strong>Well done!</strong> You successfully read this important alert message.
		<button type="button" class="close" data-dismiss="alert" aria-label="Close">
				<span aria-hidden="true">
				<i class="now-ui-icons ui-1_simple-remove"></i>
			</span>
		</button>
	</div>
</div>
<div class="alert alert-info" role="alert">
	<div class="container">
		<div class="alert-icon">
			<i class="now-ui-icons travel_info"></i>
		</div>
		 <strong>Heads up!</strong> This alert needs your attention, but it's not super important.
		<button type="button" class="close" data-dismiss="alert" aria-label="Close">
				<span aria-hidden="true">
				<i class="now-ui-icons ui-1_simple-remove"></i>
			</span>
		</button>
	</div>
</div>
<div class="alert alert-warning" role="alert">
	<div class="container">
		<div class="alert-icon">
			<i class="now-ui-icons ui-1_bell-53"></i>
		</div>
		<strong>Warning!</strong> Better check yourself, you're not looking too good.
		<button type="button" class="close" data-dismiss="alert" aria-label="Close">
			<span aria-hidden="true">
				<i class="now-ui-icons ui-1_simple-remove"></i>
			</span>
		</button>
	</div>
</div>
<div class="alert alert-danger" role="alert">
	<div class="container">
		<div class="alert-icon">
			<i class="now-ui-icons objects_support-17"></i>
		</div>
		<strong>Oh snap!</strong> Change a few things up and try submitting again.
		<button type="button" class="close" data-dismiss="alert" aria-label="Close">
			<span aria-hidden="true">
				<i class="now-ui-icons ui-1_simple-remove"></i>
			</span>
		</button>
	</div>
</div>


    <div class="alert alert-success" role="alert">
    	<div class="container">
    		<div class="alert-icon">
    			<i class="now-ui-icons ui-2_like"></i>
    		</div>
    		<strong>Well done!</strong> You successfully read this important alert message.
    		<button type="button" class="close" data-dismiss="alert" aria-label="Close">
    				<span aria-hidden="true">
    				<i class="now-ui-icons ui-1_simple-remove"></i>
    			</span>
    		</button>
    	</div>
    </div>
    <div class="alert alert-info" role="alert">
    	<div class="container">
    		<div class="alert-icon">
    			<i class="now-ui-icons travel_info"></i>
    		</div>
    		 <strong>Heads up!</strong> This alert needs your attention, but it's not super important.
    		<button type="button" class="close" data-dismiss="alert" aria-label="Close">
    				<span aria-hidden="true">
    				<i class="now-ui-icons ui-1_simple-remove"></i>
    			</span>
    		</button>
    	</div>
    </div>
    <div class="alert alert-warning" role="alert">
    	<div class="container">
    		<div class="alert-icon">
    			<i class="now-ui-icons ui-1_bell-53"></i>
    		</div>
    		<strong>Warning!</strong> Better check yourself, you're not looking too good.
    		<button type="button" class="close" data-dismiss="alert" aria-label="Close">
    			<span aria-hidden="true">
    				<i class="now-ui-icons ui-1_simple-remove"></i>
    			</span>
    		</button>
    	</div>
    </div>
    <div class="alert alert-danger" role="alert">
    	<div class="container">
    		<div class="alert-icon">
    			<i class="now-ui-icons objects_support-17"></i>
    		</div>
    		<strong>Oh snap!</strong> Change a few things up and try submitting again.
    		<button type="button" class="close" data-dismiss="alert" aria-label="Close">
    			<span aria-hidden="true">
    				<i class="now-ui-icons ui-1_simple-remove"></i>
    			</span>
    		</button>
    	</div>
    </div>

</br>
## Sections
We have created two options for the background of sections. You can go with a `black`, `gray` or `orange` color. We built an attribute named `data-background-color="color"`, so at once you add this attribute to div with class `.section` you can access our three background options color. To see how they look, you can check them out below.

<div class="row">
<div class="col-md-1">
    <span class="pick-class-label label-tooltip" data-background-color="orange" data-toggle="tooltip" data-placement="right" title="" data-original-title="data-background-color='orange'"> </span>
</div>
<div class="col-md-1">
    <span class="pick-class-label label-tooltip" data-background-color="black" data-toggle="tooltip" data-placement="right" title="" data-original-title="data-background-color='black'"> </span>
</div>
<div class="col-md-1">
    <span class="pick-class-label label-tooltip" data-background-color="gray" data-toggle="tooltip" data-placement="right" title="" data-original-title="data-background-color='gray'"> </span>
</div>
</div>

</br>
## Changing Colors (SASS)

You can change the default colors via variables from SASS:

1. You can find the colors in `assets/scss/now-ui-kit/_variables.scss` starting with line 72 where is the primary color set: $brand-primary: $primary-color !default;.
2. Add the SASS folder from assets/scss/ to a new project inside Koala Compiler and find the file now-ui-kit.scss, it will be the one in Green.
3. Right click on that file and set the output path, it must be in assets/css/ so anything that you compile will overwrite the original now-ui-kit.css
4. Press on compile and everything will be done automatically.

<!-- Control Center for Now Ui Kit: parallax effects, scripts for the example pages etc -->
<script src="js/now-ui-kit.js" type="text/javascript"></script>

</br>
## Modify / Recompile the SASS

1. Download the project’s zip
2. Make sure you have node.js (https://nodejs.org/en/) installed
3. ype npm install in terminal/console in the source folder where package.json is located
4. You will find all the branding colors inside assets/scss/variables/_brand.scss. You can change them with a HEX value or with other predefined variables from assets/scss/variables/_colors.scss
5. Run in terminal gulp compile:scss for a single compilation or gulp watch for continous compilation of the changes that you make in *.scss files. This command should be run in the same folder where gulpfile.js and package.json are located
