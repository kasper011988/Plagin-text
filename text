<?php
/*
Plugin Name: readln text
Description: readln text
Version: 1.0
Author: Karmachev Aleksandr (Kasper)
Author URI: http://
*/
function insertFootNote($content) {

if(!is_feed() && !is_home()) {

$content.= "<div class='subscribe'>";

$content.= "<h4>Понравилась статья?</h4>";

$content.= "<p>Подпишись на нашу  <a href='http://feeds2.feedburner.com/wprecipe'>RSS ленту</a> и никогда не пропускай наши рецепты!</p>";

$content.= "</div>";

}

return $content;

}

add_filter ('the_content', 'insertFootNote');
