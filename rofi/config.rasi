configuration {
  modi:			"window,drun,filebrowser";
  sidebar-mode:		true;
  show-icons:		false;
  sort:			true;
  sorting-method:	"normal";
  disable-history:	false;
  scroll-method:	0;
  drun-display-format:	"{name}";
  matching:		"fuzzy";
  window-thumbnail:	true;
  display-drun:		"Apps";
  display-window:	"Windows";
  display-filebrowser:	"Files";

filebrowser {
  directories-first:	true;
  sorting-method:	"name";
  }
}

@theme "/dev/null"

* {
  bg:		#0C0F09;
  fg:		#05E289;
  bgAlt: #1B1E25;
  button:		#05E289;
  background-color:	@bg;
  text-color:		@fg;
}

@import "./Themes/style.rasi"

mainbox { children: [ mode-switcher, inputbar, listview ]; }

window {
  transparency:		"real";
  width:		650px;
  border-radius:	15px;
  height:		500px;
  border: 12px;
  border-color: @bg;
}

inputbar {
  children:		[ entry ];
  expand:		false;
  padding:		5px 10px 5px 10px;
}

prompt { 
  enabled: true; 
  background-color:	@bgAlt;
  padding:		15px;
  border-radius:	15px;
}

entry {
  background-color:	@bgAlt;
  placeholder:		"Search";
  expand:		true;
  padding:		15px;
  border-radius:	15px;
}

listview {
  columns:		2;
  cycle:		true;
  dynamic:		true;
  layout:		vertical;
  scrollbar:		false;
}

element {
  orientation:		vertical;
  margin:		2px 3px 2px 3px;
  border-radius:	10px;
  background-color:	@bgAlt;
}

element-text {
  expand:		true;
  margin:		15px 15px 15px 15px;
  background-color:	inherit;
  text-color:		inherit;
}

element selected {
  background-color:	@fg;
  text-color:		@bgAlt;
  border-radius:	10px;
}

mode-switcher {
  spacing:		2px;
  border-radius:	10px;
  background-color:	inherit;
  text-color:		inherit;
  margin:		10px 50px 10px 50px;
}

button {
  padding:		8px;
  background-color:	@bgAlt;
  vertical-align:	0.5; 
  horizontal-align:	0.5;
}

button selected {
  padding:		8px;
  background-color:	@fg;
  text-color:		@bgAlt;
}
