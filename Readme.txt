The jQuery Ajax samples can be found in the following folders:

UsingAjax
UsingGet
UsingLoad
UsingPost
UsingSerialize

Visual Studio 2010 or higher is required to run these demos.

jQuery Ajax functions

jQuery provides several functions that can be used to send and receive data:
$(selector).load() - loads HTML data from the server
$.get() and $.post() : get and post raw data from the server
$.getJSON() : get / post and return JSON data
$.ajax()   : provides core functionality, the most low-level API

Using load()

$(selector).load(url,data,callback) allows HTML content to be loaded from a server and added to a DOM object:

$(document).ready(function(){
	$('#HelpButton').click(function(){
	})
})


