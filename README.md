# Angular2 Pipe Collection

If you find this information usefull don't forget to Star or Fork, thank you.

## Angular2 Capitalize Pipe 

Use as is 

## Angular2 Filter Pipe || Search Pipe

With this pipe you can search for values inside an array of objects, and the object / objects that matches the search criteria will be returned. 

Keep in mind that title, status, priority...  are keys from my object, you will need  to edit and adapt them to match your object keys.

Usage:

`<div *ngFor="let list of lists | filter:'some words' ">{{list.something}}</div>
`
## Angular2 Markdown to Html Pipe

If you are using Angular CLI beta-18 or Angular 2.1.0 
If you using CLI first install:

npm i marked --save
npm i @types/marked

Make the import inside the pipe:
import * as marked from 'marked';

Using your pipe
Import your pipe into your component:
import {MarkdownToHtmlPipe } from "./markdown-to-html.pipe";

To use your pipe, you will need to bind it to the [innerHTML] property on an element in your template.

<section id="markdown-in-here" [innerHTML]="defaultContent | markdown">
    <!-- Markdown will appear here in the DOM -->
</section>

[Original documentation](https://www.reddit.com/r/Angular2/comments/4s2xda/keep_getting_errors_trying_to_import_marked_into/)

## Angular2 Name Initials Pipe

Extracts the Initials from names and capitalize them. 
Used as is.

## Angular2 Substring Pipe 

Cuts the text at a specific index, keep in mind is not made to keep track of words.
Usage {{something | substring: '10'}}


## Angular2 Order By Pipe

This pipe can be used to sort tables, very usefull if you make your own table. Many thanks to Stacy Gay Fuel-Ui.

Documentation: https://github.com/FuelInteractive/fuel-ui  http://fuelinteractive.github.io/fuel-ui/#/pipe/orderby





