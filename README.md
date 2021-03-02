@import url('https://fonts.googleapis.com/css?family=Montserrat:400,700|Noto+Serif:400,400i,700,700i');
@import url('https://fonts.googleapis.com/icon?family=Material+Icons');
@import url('https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.11.2/css/all.css?v=3.2.0.3');
@import url('https://maxcdn.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css?v=3.2.0.3');
@import url('https://cdn.rawgit.com/jpswalsh/academicons/master/css/academicons.min.css?v=3.2.0.3');
html {
    line-height: 1.15;
    -ms-text-size-adjust: 100%;
    -webkit-text-size-adjust: 100%;
}
body {
    margin: 0;
}
article,
aside,
footer,
header,
nav,
section {
    display: block;
}
h1 {
    font-size: 2em;
    margin: 0.67em 0;
}
figcaption,
figure,
main {
    display: block;
}
figure {
    margin: 1em 40px;
}
hr {
    box-sizing: content-box;
    height: 0;
    overflow: visible;
}
pre {
    font-family: monospace, monospace;
    font-size: 1em;
}
a {
    background-color: transparent;
    -webkit-text-decoration-skip: objects;
}
abbr[title] {
    border-bottom: none;
    text-decoration: underline;
    text-decoration: underline dotted;
}
b,
strong {
    font-weight: inherit;
}
b,
strong {
    font-weight: bolder;
}
code,
kbd,
samp {
    font-family: monospace, monospace;
    font-size: 1em;
}
dfn {
    font-style: italic;
}
mark {
    background-color: #ff0;
    color: #000;
}
small {
    font-size: 80%;
}
sub,
sup {
    font-size: 75%;
    line-height: 0;
    position: relative;
    vertical-align: baseline;
}
sub {
    bottom: -0.25em;
}
sup {
    top: -0.5em;
}
audio,
video {
    display: inline-block;
}
audio:not([controls]) {
    display: none;
    height: 0;
}
img {
    border-style: none;
}
svg:not(:root) {
    overflow: hidden;
}
button,
input,
optgroup,
select,
textarea {
    font-family: sans-serif;
    font-size: 100%;
    line-height: 1.15;
    margin: 0;
}
button,
input {
    overflow: visible;
}
button,
select {
    text-transform: none;
}
button,
html [type="button"],
[type="reset"],
[type="submit"] {
    -webkit-appearance: button;
}
button::-moz-focus-inner,
[type="button"]::-moz-focus-inner,
[type="reset"]::-moz-focus-inner,
[type="submit"]::-moz-focus-inner {
    border-style: none;
    padding: 0;
}
button:-moz-focusring,
[type="button"]:-moz-focusring,
[type="reset"]:-moz-focusring,
[type="submit"]:-moz-focusring {
    outline: 1px dotted ButtonText;
}
fieldset {
    padding: 0.35em 0.75em 0.625em;
}
legend {
    box-sizing: border-box;
    color: inherit;
    display: table;
    max-width: 100%;
    padding: 0;
    white-space: normal;
}
progress {
    display: inline-block;
    vertical-align: baseline;
}
textarea {
    overflow: auto;
}
[type="checkbox"],
[type="radio"] {
    box-sizing: border-box;
    padding: 0;
}
[type="number"]::-webkit-inner-spin-button,
[type="number"]::-webkit-outer-spin-button {
    height: auto;
}
[type="search"] {
    -webkit-appearance: textfield;
    outline-offset: -2px;
}
[type="search"]::-webkit-search-cancel-button,
[type="search"]::-webkit-search-decoration {
    -webkit-appearance: none;
}
::-webkit-file-upload-button {
    -webkit-appearance: button;
    font: inherit;
}
details,
menu {
    display: block;
}
summary {
    display: list-item;
}
canvas {
    display: inline-block;
}
template {
    display: none;
}
[hidden] {
    display: none;
}
*,
*:before,
*:after {
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    box-sizing: border-box;
}
@keyframes pkp_spin {
    0% {
        transform: rotateZ(-360deg);
        -webkit-transform: rotateZ(-360deg);
        -moz-transform: rotateZ(-360deg);
        -o-transform: rotateZ(-360deg);
    }
    100% {
        transform: rotateZ(0deg);
        -webkit-transform: rotateZ(0deg);
        -moz-transform: rotateZ(0deg);
        -o-transform: rotateZ(0deg);
    }
}
@-webkit-keyframes pkp_spin {
    0% {
        transform: rotateZ(-360deg);
        -webkit-transform: rotateZ(-360deg);
        -moz-transform: rotateZ(-360deg);
        -o-transform: rotateZ(-360deg);
    }
    100% {
        transform: rotateZ(0deg);
        -webkit-transform: rotateZ(0deg);
        -moz-transform: rotateZ(0deg);
        -o-transform: rotateZ(0deg);
    }
}
@-moz-keyframes pkp_spin {
    0% {
        transform: rotateZ(-360deg);
        -webkit-transform: rotateZ(-360deg);
        -moz-transform: rotateZ(-360deg);
        -o-transform: rotateZ(-360deg);
    }
    100% {
        transform: rotateZ(0deg);
        -webkit-transform: rotateZ(0deg);
        -moz-transform: rotateZ(0deg);
        -o-transform: rotateZ(0deg);
    }
}
@-o-keyframes pkp_spin {
    0% {
        transform: rotateZ(-360deg);
        -webkit-transform: rotateZ(-360deg);
        -moz-transform: rotateZ(-360deg);
        -o-transform: rotateZ(-360deg);
    }
    100% {
        transform: rotateZ(0deg);
        -webkit-transform: rotateZ(0deg);
        -moz-transform: rotateZ(0deg);
        -o-transform: rotateZ(0deg);
    }
}
.pkp_button,
.pkp_button_primary,
.pkp_button_offset {
    display: inline-block;
    padding: 7px 10px;
    vertical-align: middle;
    background-color: #eee;
    background-image: linear-gradient(#eee, #ddd);
    border: 1px solid #ccc;
    border-radius: 3px;
    box-shadow: 0 1px 2px rgba(0, 0, 0, 0.1), inset 0 1px 1px rgba(255, 255, 255, 0.6);
    font-size: 12px;
    font-weight: 700;
    line-height: 16px;
    color: rgba(0, 0, 0, 0.84);
    text-shadow: 0 2px 0 rgba(255, 255, 255, 0.6);
    cursor: pointer;
    text-decoration: none;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
    -webkit-appearance: none;
}
.pkp_button:hover,
.pkp_button:focus {
    background-color: #fff;
    background-image: linear-gradient(#fff, #ddd);
    color: #000;
}
.pkp_button:active {
    background-color: #ddd;
    background-image: linear-gradient(#eee, #ccc);
}
.pkp_button[disabled],
.pkp_button_primary[disabled],
.pkp_button_offset[disabled] {
    opacity: 0.5;
    cursor: default;
}
.pkp_button_primary {
    background-color: #1b2c3d;
    background-image: linear-gradient(#2b4560, #1b2c3d);
    box-shadow: 0 1px 2px rgba(0, 0, 0, 0.1), inset 0 1px 1px rgba(255, 255, 255, 0.4);
    color: #fff;
    text-shadow: 0 2px 0 rgba(0, 0, 0, 0.2);
    border-color: #1b2c3d;
}
.pkp_button_primary:hover,
.pkp_button_primary:focus {
    text-decoration: none;
    background-color: #900;
    background-image: linear-gradient(#3a5f84, #131f2b);
    color: #fff;
}
.pkp_button_primary:active {
    background-color: #0b121a;
    background-image: linear-gradient(#23394f, #040608);
}
.pkp_button_offset {
    background-color: #d00a6c;
    background-image: linear-gradient(#f41985, #d00a6c);
    box-shadow: 0 1px 2px rgba(0, 0, 0, 0.1), inset 0 1px 1px rgba(255, 255, 255, 0.4);
    color: #fff;
    text-shadow: 0 2px 0 rgba(0, 0, 0, 0.2);
    border-color: #d00a6c;
}
.pkp_button_offset:hover,
.pkp_button_offset:focus {
    text-decoration: none;
    background-color: #b8095f;
    background-image: linear-gradient(#f64a9f, #b8095f);
    color: #fff;
}
.pkp_button_offset:active {
    background-color: #9f0853;
    background-image: linear-gradient(#e80b79, #870646);
}
.pkp_button_link,
.pkp_button_link_offset {
    display: inline-block;
    padding: 7px 10px;
    vertical-align: middle;
    font-size: 12px;
    font-weight: 700;
    line-height: 16px;
    color: #1b2c3d;
    text-shadow: 0 2px 0 rgba(255, 255, 255, 0.6);
    cursor: pointer;
    text-decoration: none;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
    -webkit-appearance: none;
}
.pkp_button_link:hover,
.pkp_button_link:focus,
.pkp_button_link_offset:hover,
.pkp_button_link_offset:focus {
    color: #900;
}
.pkp_button_link:active,
.pkp_button_link_offset:active {
    color: #0b121a;
}
.pkp_button_link[disabled],
.pkp_button_link_offset[disabled] {
    opacity: 0.5;
    cursor: default;
}
.pkp_button_link_offset {
    color: #d00a6c;
}
.pkp_button_link_offset:hover,
.pkp_button_link_offset:focus {
    color: #f64a9f;
}
.pkp_button_link_offset:active {
    color: #b50e61;
}
.pkp_spinner:after {
    display: inline-block;
    position: relative;
    width: 20px;
    height: 20px;
    vertical-align: middle;
    -webkit-animation: pkp_spin 0.6s linear infinite;
    -moz-animation: pkp_spin 0.6s linear infinite;
    -ms-animation: pkp_spin 0.6s linear infinite;
    -o-animation: pkp_spin 0.6s linear infinite;
    animation: pkp_spin 0.6s linear infinite;
    border-radius: 100%;
    border-top: 1px solid #888;
    border-bottom: 1px solid transparent;
    border-left: 1px solid #888;
    border-right: 1px solid transparent;
    border-top-color: rgba(0, 0, 0, 0.5);
    border-left-color: rgba(0, 0, 0, 0.5);
    content: "";
    opacity: 1;
}
.pkp_loading {
    font-size: 13px;
    line-height: 20px;
}
.pkp_loading .pkp_spinner {
    margin-right: 0.25em;
}
.pkp_unstyled_list,
.cmp_article_list,
.cmp_form .tagit,
.ui-autocomplete,
.cmp_breadcrumbs ol,
.cmp_announcements,
.pkp_site_nav_menu ul,
.pkp_page_index .journals ul,
.page_catalog_category .subcategories ul,
.page_issue_archive .issues_archive,
.page_register .context_optin .contexts,
.obj_article_details .authors,
.obj_article_details .galleys_links,
.obj_article_details .supplementary_galleys_links,
.obj_article_summary .galleys_links,
.obj_issue_toc .articles,
.obj_issue_toc .galleys_links,
.pkp_block .content ul {
    margin: 0;
    padding: 0;
    list-style: none;
}
.pkp_caret {
    content: " ";
    display: inline-block;
    width: 0;
    height: 0;
    border: 4px solid transparent;
    vertical-align: middle;
}
.pkp_caret_down {
    border-top: 6px solid;
}
.pkp_caret_right {
    border-left: 6px solid;
}
.pkp_screen_reader,
.cmp_skip_to_content a,
.pkp_page_index .journals h2,
.pkp_page_index .cmp_announcements h2,
.page_register .context_optin .roles legend {
    clip: rect(1px, 1px, 1px, 1px);
    position: absolute !important;
    left: -2000px;
}
.pkp_screen_reader:focus,
.pkp_page_index .cmp_announcements h2:focus {
    background-color: #fff;
    border-radius: 3px;
    box-shadow: 0 0 2px 2px rgba(0, 0, 0, 0.6);
    -webkit-box-shadow: 0 0 2px 2px rgba(0, 0, 0, 0.6);
    clip: auto !important;
    color: #000;
    display: block;
    font-size: 14px;
    height: auto;
    line-height: normal;
    padding: 10px;
    position: absolute;
    left: 5px;
    top: 5px;
    text-decoration: none;
    width: auto;
    z-index: 100000;
}
.pkp_helpers_clear:before,
.pkp_helpers_clear:after {
    content: " ";
    display: table;
}
.pkp_helpers_clear:after {
    clear: both;
}
.pkp_help_link {
    display: inline-block;
    padding: 4px 0;
    font-size: 12px;
    line-height: 16px;
    font-weight: 700;
    text-decoration: none;
    border: none;
    box-shadow: none;
    color: #1b2c3d;
    z-index: 3;
}
.pkp_help_link:hover,
.pkp_help_link:focus {
    color: #900;
}
.pkp_help_link:focus {
    outline: 0;
    box-shadow: 0 0 0 3px #1b2c3d;
    border-radius: 3px;
}
.pkp_help_tab,
.pkp_help_modal {
    position: absolute;
    top: -20px;
    right: 20px;
    padding: 5px 1em;
    background: #fff;
    border-top-left-radius: 3px;
    border-top-right-radius: 3px;
}
.pkp_help_modal {
    top: 20px;
    right: 40px;
}
.pkp_uploadedFile_summary {
    font-size: 13px;
    line-height: 20px;
}
.pkp_uploadedFile_summary .filename .display {
    line-height: 20px;
}
.pkp_uploadedFile_summary .filename .edit {
    line-height: 20px;
}
.pkp_uploadedFile_summary .details {
    margin-top: 5px;
    color: rgba(0, 0, 0, 0.54);
}
.pkp_uploadedFile_summary .details > span {
    margin-left: 20px;
}
.pkp_uploadedFile_summary .details > span:first-child {
    margin-left: 0;
}
.pkp_uploadedFile_summary .details > span:before {
    display: inline-block;
    font: normal normal normal 14px/1 FontAwesome;
    font-size: inherit;
    text-rendering: auto;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    transform: translate(0, 0);
    padding-right: 0.25em;
    color: #aaa;
}
.pkp_uploadedFile_summary .pixels:before {
    content: "\f108";
}
.pkp_uploadedFile_summary .print {
    margin-left: 20px;
}
.pkp_uploadedFile_summary .print:before {
    display: inline-block;
    font: normal normal normal 14px/1 FontAwesome;
    font-size: inherit;
    text-rendering: auto;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    transform: translate(0, 0);
    padding-right: 0.25em;
    color: #aaa;
    content: "\f02f";
}
.pkp_uploadedFile_summary .type:before {
    content: "\f016";
}
.pkp_uploadedFile_summary .type.pdf:before {
    content: "\f1c1";
}
.pkp_uploadedFile_summary .type.doc:before,
.pkp_uploadedFile_summary .type.docx:before {
    content: "\f1c2";
}
.pkp_uploadedFile_summary .type.xls:before,
.pkp_uploadedFile_summary .type.xlsx:before {
    content: "\f1c3";
}
.pkp_uploadedFile_summary .file_size:before {
    content: "\f0a0";
}
.pkp_helpers_invisible {
    visibility: hidden;
}
.pkp_helpers_display_none {
    display: none !important;
}
.pkp_helpers_align_left {
    float: left;
}
.pkp_helpers_align_right {
    float: right;
}
.pkp_helpers_text_left {
    text-align: left;
}
.pkp_helpers_text_right {
    text-align: right;
}
.pkp_helpers_text_center {
    text-align: center;
}
.pkp_helpers_text_justify {
    text-align: justify;
}
.pkp_helpers_title_padding {
    padding: 5px !important;
}
.pkp_helpers_image_left {
    float: left;
    margin: 4px 10px 4px 0;
}
.pkp_helpers_image_right {
    float: right;
    margin: 4px 0 4px 10px;
}
.pkp_helpers_container_center {
    margin: 0 auto;
}
.pkp_helpers_debug,
.pkp_helpers_debug div {
    border: 1px dashed #f00;
    padding: 2px;
}
.pkp_helpers_flatlist {
    margin: 0;
    padding: 0;
}
.pkp_helpers_flatlist li {
    float: left;
    position: relative;
}
.pkp_helpers_bulletlist li {
    list-style: disc;
}
.pkp_helpers_icon_link_valign {
    line-height: 24px;
}
.pkp_helpers_moveicon {
    cursor: move;
}
.pkp_helpers_full {
    width: 100%;
}
.pkp_helpers_half {
    width: 50%;
}
.pkp_helpers_third {
    width: 33%;
}
.pkp_helpers_quarter {
    width: 25%;
}
.pkp_helpers_fifth {
    width: 20%;
}
.pkp_helpers_threeQuarter {
    width: 75%;
}
.pkp_helpers_underline:after {
    border-bottom: 2px solid #fff;
    content: " ";
    display: block;
}
.pkp_helpers_dotted_underline {
    border-bottom: 1px dotted #999;
}
.pkp_helpers_black_bg {
    background-color: black;
}
.pkp_helpers_text_warn {
    color: #d00a6c;
}
.pkp_helpers_text_primary {
    color: black;
}
.NMI_TYPE_CUSTOM_EDIT {
    display: none;
}
.pkp_controllers_extrasOnDemand {
    display: inline-block;
}
.pkp_controllers_extrasOnDemand > a {
    position: relative;
    display: block;
    padding: 0 10px 0 40px;
    border: 1px solid #ddd;
    line-height: 30px;
    text-decoration: none;
}
.pkp_controllers_extrasOnDemand > a .fa {
    position: absolute;
    top: 0;
    left: 0;
    line-height: 30px;
    width: 30px;
    text-align: center;
    border-right: 1px solid #ddd;
}
.pkp_controllers_extrasOnDemand > a .fa:before {
    display: inline-block;
    transition: transform 0.3s;
}
.pkp_controllers_extrasOnDemand > .container {
    padding: 0 10px;
    max-height: 0;
    transition: padding 0.3s;
    overflow: hidden;
}
.pkp_controllers_extrasOnDemand .toggleExtras-active {
    display: none;
}
.pkp_controllers_extrasOnDemand.active .toggleExtras-active {
    display: block;
}
.pkp_controllers_extrasOnDemand.active .toggleExtras-inactive {
    display: none;
}
.pkp_controllers_extrasOnDemand.active > a .fa:before {
    -webkit-transform: rotate(45deg);
    -ms-transform: rotate(45deg);
    transform: rotate(45deg);
}
.pkp_controllers_extrasOnDemand.active > .container {
    padding: 10px;
    max-height: none;
    border: 1px solid #ddd;
    border-top: none;
    overflow: auto;
}
.pkp_controllers_extrasOnDemand > a:hover,
.pkp_controllers_extrasOnDemand > a:focus,
.pkp_controllers_extrasOnDemand.active > a {
    color: #fff;
    background: #1b2c3d;
    border-color: #1b2c3d;
}
.pkp_controllers_extrasOnDemand > a:hover .fa,
.pkp_controllers_extrasOnDemand > a:focus .fa,
.pkp_controllers_extrasOnDemand.active > a .fa {
    border-color: rgba(255, 255, 255, 0.2);
}
.row:before,
.row:after {
    content: " ";
    display: table;
}
.row:after {
    clear: both;
}
.cmp_button,
.cmp_form .buttons button,
.pkp_search button[type="submit"],
.page_lost_password .buttons button,
.page_search .submit button,
.block_make_submission a {
    display: inline-block;
    padding: 0 1em;
    background: #eee;
    border: 1px solid rgba(0, 0, 0, 0.4);
    border-top-color: #bbb;
    border-radius: 3px;
    box-shadow: inset 0 -1em 1em rgba(0, 0, 0, 0.1);
    font-size: 13px;
    line-height: 28px;
    font-weight: 700;
    color: #1b2c3d;
    text-decoration: none;
}
.cmp_button:hover,
.cmp_button:focus,
.page_search .submit button:hover,
.page_search .submit button:focus {
    box-shadow: inset 0 1em 1em rgba(0, 0, 0, 0.1);
}
.cmp_button_wire,
.obj_galley_link {
    display: inline-block;
    padding: 0 1em;
    background: #fff;
    border: 1px solid #1b2c3d;
    border-radius: 3px;
    font-size: 13px;
    line-height: 28px;
    color: #1b2c3d;
    text-decoration: none;
}
.cmp_button_wire:hover,
.cmp_button_wire:focus,
.obj_galley_link:hover,
.obj_galley_link:focus {
    background: #1b2c3d;
    color: #fff;
}
.cmp_article_list > li {
    margin-bottom: 30px;
}
.cmp_article_list > li:before,
.cmp_article_list > li:after {
    content: " ";
    display: table;
}
.cmp_article_list > li:after {
    clear: both;
}
.cmp_form fieldset {
    margin: 0 0 20px;
    padding: 0;
    border: none;
}
.cmp_form legend {
    margin-bottom: 10px;
    font-size: 16px;
    font-weight: 700;
    line-height: 20px;
}
.cmp_form .fields > div {
    position: relative;
    padding-bottom: 30px;
}
.cmp_form .fields > div .error {
    position: absolute;
    left: 0.5em;
    bottom: 11px;
    padding: 0 0.5em;
    background: #ff4040;
    border-bottom-left-radius: 3px;
    border-bottom-right-radius: 3px;
    font-size: 13px;
    line-height: 20px;
    font-weight: 700;
    color: #fff;
}
.cmp_form label {
    display: block;
    cursor: pointer;
}
.cmp_form .label {
    display: block;
    font-size: 13px;
    font-weight: 400;
    font-style: italic;
}
.cmp_form .label .required {
    color: #ff4040;
}
.cmp_form input[type="text"],
.cmp_form input[type="email"],
.cmp_form input[type="password"],
.cmp_form input[type="url"],
.cmp_form input[type="phone"],
.cmp_form select,
.cmp_form textarea,
.cmp_form .tagit,
.pkp_search input[type="text"] {
    padding: 0 0.5em;
    width: 100%;
    height: 28px;
    background: #fff;
    border: 1px solid rgba(0, 0, 0, 0.4);
    border-radius: 3px;
    font-size: 13px;
    line-height: 28px;
}
.cmp_form textarea {
    width: 100%;
    height: 8em;
}
.cmp_form .pkp_form_error {
    margin-bottom: 10px;
    border-radius: 3px;
    padding: 0 0.5em;
    font-weight: 700;
    font-size: 13px;
    background: #ff4040;
    color: #fff;
}
.cmp_form label > input[type="checkbox"],
.cmp_form label > input[type="radio"] {
    margin-right: 0.25em;
}
.cmp_form .buttons:before,
.cmp_form .buttons:after {
    content: " ";
    display: table;
}
.cmp_form .buttons:after {
    clear: both;
}
.cmp_form .buttons a {
    font-size: 13px;
    line-height: 30px;
    margin-left: 1em;
}
.cmp_form .description {
    margin-top: 0;
    font-size: 12px;
    line-height: 1.5em;
    color: rgba(0, 0, 0, 0.54);
}
@media (min-width: 480px) {
    .cmp_form input[type="text"],
    .cmp_form input[type="email"],
    .cmp_form input[type="password"],
    .cmp_form input[type="url"],
    .cmp_form input[type="phone"],
    .cmp_form select,
    .cmp_form .tagit,
    .pkp_search input[type="text"] {
        max-width: 20em;
    }
}
.cmp_form .tagit {
    max-width: 100%;
    height: auto;
}
.cmp_form .tagit:before,
.cmp_form .tagit:after {
    content: " ";
    display: table;
}
.cmp_form .tagit:after {
    clear: both;
}
.cmp_form .tagit > li {
    display: inline-block;
}
.cmp_form .tagit > li.tagit-choice {
    margin-right: 0.5em;
    padding-left: 0.5em;
    background: #ddd;
    border-radius: 3px;
    line-height: 20px;
}
.cmp_form .tagit input[type="text"] {
    display: inline-block;
    border: none;
    width: inherit;
    line-height: 30px;
    height: 30px;
    vertical-align: top;
    padding: 0 0.5em;
}
.cmp_form .tagit-close {
    padding: 0 0.5em;
    color: #ff4040;
}
.ui-autocomplete {
    width: 20em;
    padding: 2px;
    border-radius: 3px;
    background: #d4d7d9;
}
.ui-autocomplete:before {
    content: "";
    position: absolute;
    top: -5px;
    left: 1em;
    width: 0;
    height: 0;
    color: #d4d7d9;
    border-bottom: 5px solid;
    border-right: 5px solid transparent;
    border-left: 5px solid transparent;
    vertical-align: middle;
}
.ui-autocomplete > li {
    padding: 5px;
    font-size: 13px;
    line-height: 20px;
    color: #fff;
    cursor: pointer;
}
.ui-autocomplete > li:hover,
.ui-autocomplete > li:focus {
    background: #fff;
    color: rgba(0, 0, 0, 0.87);
}
.cmp_pagination {
    text-align: right;
}
.cmp_pagination:before,
.cmp_pagination:after {
    content: " ";
    display: table;
}
.cmp_pagination:after {
    clear: both;
}
.cmp_pagination .prev {
    float: left;
    margin-right: 0.5em;
    text-decoration: none;
}
.cmp_pagination .prev:before {
    display: inline-block;
    font: normal normal normal 14px/1 FontAwesome;
    font-size: inherit;
    text-rendering: auto;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    transform: translate(0, 0);
    content: "\f177";
    margin-right: 0.5em;
}
.cmp_pagination .next {
    margin-left: 0.5em;
    text-decoration: none;
}
.cmp_pagination .next:after {
    display: inline-block;
    font: normal normal normal 14px/1 FontAwesome;
    font-size: inherit;
    text-rendering: auto;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    transform: translate(0, 0);
    content: "\f178";
    margin-left: 0.5em;
}
.cmp_edit_link {
    display: inline-block;
    margin-left: 1em;
    font-size: 13px;
    font-weight: 400;
    line-height: 1;
    vertical-align: middle;
    text-decoration: none;
}
.cmp_edit_link:before {
    display: inline-block;
    font: normal normal normal 14px/1 FontAwesome;
    font-size: inherit;
    text-rendering: auto;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    transform: translate(0, 0);
    content: "\f040";
}
.cmp_search_filter {
    margin-bottom: 10px;
    font-size: 13px;
}
.cmp_search_filter:last-child {
    margin-bottom: 0;
}
.cmp_search_filter label {
    font-style: italic;
}
.cmp_search_filter .delete {
    color: #ff4040;
}
.cmp_notification {
    display: block;
    width: 100%;
    padding: 20px;
    margin-bottom: 40px;
    background: #ddd;
    border-left: 5px solid #1b2c3d;
    font-size: 14px;
    line-height: 20px;
}
.cmp_notification .success {
    border-color: #00b24e;
}
.cmp_notification .no {
    border-color: #ff4040;
}
.cmp_breadcrumbs {
    display: inline-block;
}
.cmp_breadcrumbs ol {
    margin-bottom: 30px;
    padding: 5px 0;
    line-height: 20px;
    font-size: 13px;
}
.cmp_breadcrumbs li {
    display: inline-block;
}
.cmp_breadcrumbs a {
    display: inline-block;
    text-decoration: none;
}
.cmp_breadcrumbs .separator {
    color: rgba(0, 0, 0, 0.54);
    padding: 0 0.5em;
}
.cmp_breadcrumbs .current {
    color: rgba(0, 0, 0, 0.54);
}
.cmp_breadcrumbs .current h1 {
    margin: 0;
    font-family: "Montserrat", "Noto Serif", -apple-system, BlinkMacSystemFont, "Segoe UI", "Roboto", "Oxygen-Sans", "Ubuntu", "Cantarell", "Helvetica Neue", sans-serif;
    font-size: 13px;
    font-weight: 400;
}
.cmp_back_link {
    margin-top: 20px;
}
.cmp_announcements {
    margin-left: -10px;
    margin-right: -10px;
}
.cmp_announcements > li {
    padding: 30px 10px;
    border-bottom: 1px solid #ddd;
}
.cmp_announcements > li:last-child {
    border-bottom: none;
}
@media (min-width: 480px) {
    .cmp_announcements {
        margin-left: -20px;
        margin-right: -20px;
    }
    .cmp_announcements > li {
        padding-left: 20px;
        padding-right: 20px;
    }
}
@media (min-width: 992px) {
    .cmp_announcements {
        margin-left: -30px;
        margin-right: -30px;
    }
    .cmp_announcements > li {
        padding-left: 30px;
        padding-right: 30px;
    }
}
.cmp_skip_to_content a {
    display: block;
    padding: 1em;
    z-index: 99999;
    background: #fff;
    transform: translateX(-50%);
}
.cmp_skip_to_content a:focus {
    clip: auto;
    top: 0;
    left: 50%;
}
.cmp_table {
    width: 100%;
    border: 1px solid #ddd;
    border-bottom: none;
    border-collapse: collapse;
}
.cmp_table th,
.cmp_table td {
    padding: 0.5em;
    text-align: left;
    border-bottom: 1px solid #ddd;
}
.cmp_table th {
    font-weight: 700;
}
body {
    font-family: "Montserrat", "Noto Serif", -apple-system, BlinkMacSystemFont, "Segoe UI", "Roboto", "Oxygen-Sans", "Ubuntu", "Cantarell", "Helvetica Neue", sans-serif;
    font-size: 14px;
    line-height: 20px;
    color: rgba(0, 0, 0, 0.87);
    background: #fff;
}
a {
    color: #1b2c3d;
}
a:hover,
a:focus {
    color: #900;
}
.pkp_site_name_wrapper,
.pkp_navigation_primary_wrapper,
.pkp_navigation_user,
.pkp_search_mobile,
.pkp_structure_content,
.pkp_structure_footer {
    position: relative;
    width: 100%;
    margin: 0 auto;
    padding-left: 10px;
    padding-right: 10px;
}
.pkp_site_name_wrapper:before,
.pkp_navigation_primary_wrapper:before,
.pkp_navigation_user:before,
.pkp_search_mobile:before,
.pkp_structure_content:before,
.pkp_structure_footer:before,
.pkp_site_name_wrapper:after,
.pkp_navigation_primary_wrapper:after,
.pkp_navigation_user:after,
.pkp_search_mobile:after,
.pkp_structure_content:after,
.pkp_structure_footer:after {
    content: " ";
    display: table;
}
.pkp_site_name_wrapper:after,
.pkp_navigation_primary_wrapper:after,
.pkp_navigation_user:after,
.pkp_search_mobile:after,
.pkp_structure_content:after,
.pkp_structure_footer:after {
    clear: both;
}
@media (min-width: 768px) {
    .pkp_site_name_wrapper,
    .pkp_navigation_primary_wrapper,
    .pkp_navigation_user,
    .pkp_search_mobile,
    .pkp_structure_content,
    .pkp_structure_footer {
        width: 728px;
        padding: 0;
    }
}
@media (min-width: 992px) {
    .pkp_site_name_wrapper,
    .pkp_navigation_primary_wrapper,
    .pkp_navigation_user,
    .pkp_search_mobile,
    .pkp_structure_content,
    .pkp_structure_footer {
        width: 952px;
    }
}
@media (min-width: 1200px) {
    .pkp_site_name_wrapper,
    .pkp_navigation_primary_wrapper,
    .pkp_navigation_user,
    .pkp_search_mobile,
    .pkp_structure_content,
    .pkp_structure_footer {
        width: 1160px;
    }
}
.has_site_logo .pkp_site_name,
.has_site_logo .pkp_navigation_primary_wrapper {
    width: auto;
}
.has_site_logo .pkp_head_wrapper {
    position: relative;
    width: 100%;
    margin: 0 auto;
    padding-right: 10px;
}
.has_site_logo .pkp_head_wrapper:before,
.has_site_logo .pkp_head_wrapper:after {
    content: " ";
    display: table;
}
.has_site_logo .pkp_head_wrapper:after {
    clear: both;
}
@media (min-width: 768px) {
    .has_site_logo .pkp_head_wrapper {
        width: 728px;
        padding-left: 0;
        padding-right: 0;
    }
}
@media (min-width: 992px) {
    .has_site_logo .pkp_head_wrapper {
        width: 952px;
    }
}
@media (min-width: 1200px) {
    .has_site_logo .pkp_head_wrapper {
        width: 1160px;
    }
}
.pkp_structure_main {
    padding: 10px;
}
@media (min-width: 480px) {
    .pkp_structure_main {
        padding: 20px;
    }
}
@media (min-width: 768px) {
    .pkp_structure_main:before,
    .pkp_structure_main:after {
        content: "";
        position: absolute;
        top: 0;
        left: 0;
        bottom: 0;
        width: 1px;
        background: #ddd;
    }
    .pkp_structure_main:after {
        left: 728px;
    }
}
@media (min-width: 992px) {
    .pkp_structure_content {
        padding-top: 30px;
    }
    .pkp_structure_sidebar {
        float: right;
        width: 300px;
    }
    .pkp_structure_main {
        float: left;
        padding: 0 30px 90px;
        width: 652px;
    }
    .pkp_structure_main:after {
        left: 652px;
    }
}
@media (min-width: 1200px) {
    .pkp_structure_main {
        width: 860px;
    }
    .pkp_structure_main:after {
        left: 860px;
    }
}
@media (min-width: 992px) {
    .pkp_structure_main:first-child:last-child {
        float: none;
        margin-left: auto;
        margin-right: auto;
        margin-top: 40px;
    }
    .pkp_structure_main:first-child:last-child:before {
        left: 150px;
    }
    .pkp_structure_main:first-child:last-child:after {
        left: auto;
        right: 150px;
    }
}
img {
    max-width: 100%;
    width: auto;
    height: auto;
}
.pkp_structure_head {
    background-color: #d4d7d9;
    border-bottom: 1px solid #ddd;
}
.pkp_head_wrapper {
    position: relative;
}
.pkp_site_name_wrapper {
    height: 40px;
}
@media (min-width: 992px) {
    .pkp_site_name_wrapper {
        height: auto;
    }
}
.pkp_site_name {
    position: absolute;
    left: 40px;
    right: 0;
    margin-top: 0;
    margin-bottom: 0;
    padding-left: 10px;
    text-align: left;
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;
    color: rgba(0, 0, 0, 0.84);
    font-family: "Montserrat", -apple-system, BlinkMacSystemFont, "Segoe UI", "Roboto", "Oxygen-Sans", "Ubuntu", "Cantarell", "Helvetica Neue", sans-serif;
    font-size: 13px;
}
.pkp_site_name > a {
    padding-top: 10px;
    padding-bottom: 10px;
}
.pkp_site_name > a:focus {
    outline: 0;
}
.pkp_site_name .is_img {
    display: inline-block;
    padding-top: 5px;
    padding-bottom: 5px;
}
.pkp_site_name .is_img:focus {
    box-shadow: 0 0 1px rgba(0, 0, 0, 0.84);
}
.pkp_site_name .is_img img {
    display: block;
    max-height: 30px;
    max-width: 100%;
    width: auto;
    height: auto;
}
.pkp_site_name .is_text {
    font-family: "Montserrat", -apple-system, BlinkMacSystemFont, "Segoe UI", "Roboto", "Oxygen-Sans", "Ubuntu", "Cantarell", "Helvetica Neue", sans-serif;
    font-size: 13px;
    font-weight: 700;
    line-height: 40px;
    color: rgba(0, 0, 0, 0.84);
    text-decoration: none;
}
.pkp_site_name .is_text:focus {
    text-decoration: underline;
}
.pkp_navigation_primary_wrapper {
    padding-left: 0;
    padding-right: 0;
}
.pkp_site_nav_menu {
    position: absolute;
    width: 100%;
    top: 100%;
    background: #d4d7d9;
    left: 0;
    padding: 10px;
    z-index: 9999;
}
.pkp_site_nav_menu .pkp_nav_list {
    padding-left: 0;
    margin-left: 0;
}
.pkp_site_nav_menu ul ul {
    padding-left: 0.5rem;
}
.pkp_site_nav_menu a {
    display: inline-block;
    padding: 0.125rem 0;
    color: #fff;
    text-decoration: none;
}
.pkp_site_nav_menu a:hover,
.pkp_site_nav_menu a:focus {
    color: #fff;
    text-decoration: underline;
}
.pkp_site_nav_menu #siteNav {
    position: absolute;
    top: 0;
    height: 0;
}
.pkp_navigation_user.pkp_navigation_user {
    margin-left: auto;
    margin-right: auto;
    margin-top: 1rem;
    padding-top: 1rem;
    border-top: 1px solid rgba(255, 255, 255, 0.1);
}
.pkp_navigation_user .task_count {
    display: inline-block;
    width: 20px;
    height: 20px;
    margin-left: 0.5em;
    border-radius: 50%;
    background: rgba(255, 255, 255, 0.3);
    line-height: 20px;
    text-align: center;
    font-size: 12px;
}
.pkp_navigation_user > li > a .task_count {
    display: none;
}
.pkp_navigation_user > li > ul a .task_count {
    display: inline-block;
    background: rgba(255, 255, 255, 0.8);
    color: #1b2c3d;
}
.pkp_navigation_user > li > ul a:hover .task_count,
.pkp_navigation_user > li > ul a:focus .task_count {
    background: #fff;
}
@media (min-width: 992px) {
    .pkp_head_wrapper {
        padding-top: 60px;
    }
    .pkp_site_nav_toggle {
        display: none;
    }
    .pkp_site_name {
        position: relative;
        width: 100%;
        left: auto;
        right: auto;
        padding: 0;
        white-space: normal;
        font-size: 2em;
        background: transparent;
    }
    .pkp_site_name .is_text {
        font-family: "Montserrat", -apple-system, BlinkMacSystemFont, "Segoe UI", "Roboto", "Oxygen-Sans", "Ubuntu", "Cantarell", "Helvetica Neue", sans-serif;
        font-size: 24px;
        line-height: 30px;
    }
    .pkp_site_name .is_img img {
        max-height: 80px;
    }
    .pkp_site_nav_menu {
        display: block;
        position: static;
        top: auto;
        padding: 0;
    }
    .pkp_site_nav_menu ul ul {
        padding-left: 0;
    }
    .has_site_logo .pkp_head_wrapper {
        padding-top: 30px;
    }
    .pkp_nav_list {
        margin: 0;
        padding: 0;
        list-style: none;
    }
    .pkp_nav_list li {
        position: relative;
        display: inline-block;
    }
    .pkp_nav_list a {
        display: inline-block;
        padding-left: 10px;
        padding-right: 10px;
        text-decoration: none;
        padding-top: 5px;
        padding-bottom: 5px;
    }
    .pkp_nav_list a:hover,
    .pkp_nav_list a:focus {
        text-decoration: none;
    }
    .pkp_nav_list ul {
        position: absolute;
        top: 100%;
        left: -9999px;
        z-index: 1000;
        width: 15em;
        margin: 0;
        padding: 0;
        background: #fff;
        border-radius: 3px;
        box-shadow: 0 0 5px rgba(0, 0, 0, 0.3);
    }
    .pkp_nav_list ul li {
        display: block;
    }
    .pkp_nav_list ul a {
        display: block;
        padding-left: 5px;
        border-left: 5px solid transparent;
        color: #1b2c3d;
    }
    .pkp_nav_list ul a:hover,
    .pkp_nav_list ul a:focus {
        outline: 0;
        background: #ddd;
        border-color: #1b2c3d;
        color: #1b2c3d;
    }
    .pkp_nav_list ul li:first-child a {
        border-top-left-radius: 3px;
        border-top-right-radius: 3px;
    }
    .pkp_nav_list ul li:last-child a {
        border-bottom-left-radius: 3px;
        border-bottom-right-radius: 3px;
    }
    .pkp_nav_list > li:hover ul {
        left: 0;
    }
    .pkp_nav_list [aria-haspopup]:after {
        position: relative;
        display: inline-block;
        content: "";
        width: 0;
        height: 0;
        margin-left: 0.25em;
        border-top: 4px solid;
        border-right: 4px solid transparent;
        border-left: 4px solid transparent;
        vertical-align: middle;
        overflow: hidden;
    }
    .pkp_navigation_primary {
        text-align: center;
    }
    .pkp_navigation_primary > li > a {
        margin: 0 1em;
        padding: 10px 0 8px;
        border-bottom: 2px solid transparent;
        color: rgba(0, 0, 0, 0.84);
        text-decoration: none;
    }
    .pkp_navigation_primary > li > a:hover,
    .pkp_navigation_primary > li > a:focus {
        color: rgba(0, 0, 0, 0.84);
        outline: 0;
        border-color: rgba(0, 0, 0, 0.84);
    }
    .pkp_navigation_primary > li:first-child a {
        margin-left: 0;
    }
    .pkp_navigation_primary > li:last-child a {
        margin-right: 0;
    }
    .pkp_navigation_primary > li:hover ul {
        left: 14px;
    }
    .pkp_navigation_primary ul a {
        padding-top: 10px;
        padding-bottom: 10px;
    }
    .pkp_navigation_primary [aria-haspopup]:hover {
        border-color: transparent;
    }
    .pkp_navigation_primary .dropdown-menu a:focus,
    .pkp_navigation_primary .dropdown-menu a:hover {
        border-color: #1b2c3d;
    }
    .dropdown-menu {
        display: none;
    }
    .dropdown-menu.show {
        display: block;
    }
    [data-toggle="dropdown"]:hover + .dropdown-menu,
    .dropdown-menu:hover {
        display: block;
    }
    .pkp_navigation_user_wrapper {
        position: absolute;
        top: 0;
        left: 50%;
        transform: translateX(-50%);
        padding-left: 10px;
        padding-right: 10px;
        text-align: right;
        padding-top: 0;
        margin-top: 0;
        border-top: none;
        z-index: 1000;
    }
    .pkp_navigation_user {
        text-align: right;
        font-size: 13px;
        padding-right: 20px;
    }
    .pkp_navigation_user.pkp_navigation_user {
        margin: 0;
        padding: 0;
        border: none;
    }
    .pkp_navigation_user li {
        text-align: left;
    }
    .pkp_navigation_user a {
        padding-top: 5px;
        padding-bottom: 5px;
        line-height: 20px;
    }
    .pkp_navigation_user > li > a:focus {
        outline: 0;
        border-bottom: 2px solid;
    }
    .pkp_navigation_user ul {
        width: 10em;
    }
    .pkp_navigation_user > li:hover ul {
        right: 0;
        left: auto;
    }
    .pkp_navigation_user > li > a,
    .pkp_navigation_user > li.in_focus > a,
    .pkp_navigation_user > li > a:hover,
    .pkp_navigation_user > li > a:focus {
        color: rgba(0, 0, 0, 0.84);
    }
    .pkp_navigation_user > li:last-child > a {
        padding-right: 0;
    }
    .pkp_navigation_user > li > a .task_count {
        display: inline-block;
    }
    .pkp_navigation_user > li > ul a .task_count {
        background: rgba(0, 0, 0, 0.2);
    }
}
@media (min-width: 992px) and (min-width: 992px) {
    .pkp_navigation_primary {
        display: inline-block;
        max-width: 80%;
        text-align: left;
    }
}
.pkp_structure_main h1 {
    font-family: "Montserrat", -apple-system, BlinkMacSystemFont, "Segoe UI", "Roboto", "Oxygen-Sans", "Ubuntu", "Cantarell", "Helvetica Neue", sans-serif;
    font-size: 24px;
    line-height: 30px;
    font-weight: 700;
}
.pkp_structure_main h2 {
    font-family: "Montserrat", -apple-system, BlinkMacSystemFont, "Segoe UI", "Roboto", "Oxygen-Sans", "Ubuntu", "Cantarell", "Helvetica Neue", sans-serif;
    font-size: 18px;
    line-height: 30px;
    font-weight: 700;
}
.pkp_structure_main h3 {
    font-family: "Montserrat", -apple-system, BlinkMacSystemFont, "Segoe UI", "Roboto", "Oxygen-Sans", "Ubuntu", "Cantarell", "Helvetica Neue", sans-serif;
    font-size: 16px;
    line-height: 20px;
    font-weight: 700;
}
.pkp_structure_main h4 {
    font-size: 14px;
    line-height: 20px;
    font-weight: 700;
}
.pkp_structure_main h5 {
    font-size: 14px;
    line-height: 20px;
    font-weight: 400;
}
.pkp_structure_main h6 {
    font-size: 13px;
    line-height: 20px;
    font-weight: 700;
}
.pkp_structure_main h1,
.pkp_structure_main h2,
.pkp_structure_main h3,
.pkp_structure_main h4 {
    margin: 40px 0 20px;
}
.pkp_structure_main h5,
.pkp_structure_main h6 {
    margin: 20px 0;
}
.pkp_structure_main p {
    line-height: 25px;
    margin: 20px 0;
}
.pkp_structure_main p:last-child {
    margin-bottom: 0;
}
.pkp_structure_main .page h1 {
    margin-top: 0;
}
.pkp_structure_main .page > .cmp_edit_link {
    float: right;
    padding: 5px 0;
    line-height: 30px;
}
.pkp_structure_main .page .monograph_count {
    float: right;
    padding: 10px 0;
    font-size: 13px;
    color: rgba(0, 0, 0, 0.54);
}
.pkp_structure_main .page .about_section {
    color: rgba(0, 0, 0, 0.54);
    line-height: 30px;
}
.pkp_structure_main .page .about_section:before,
.pkp_structure_main .page .about_section:after {
    content: " ";
    display: table;
}
.pkp_structure_main .page .about_section:after {
    clear: both;
}
.pkp_structure_main .page .about_section .cover {
    float: right;
    width: 20%;
    margin-left: 10%;
    margin-right: 10%;
}
.pkp_structure_main .page .about_section .cover img {
    display: block;
    margin: 0 auto;
}
.pkp_structure_main .page .about_section .description p:first-child {
    margin-top: 0;
}
.pkp_structure_main .page .about_section .description p:last-child {
    margin-bottom: 0;
}
@media (min-width: 480px) {
    .pkp_structure_main .page .about_section {
        font-size: 16px;
        font-style: italic;
    }
}
.pkp_site_nav_toggle {
    position: absolute;
    top: 0;
    left: 0;
    width: 40px;
    height: 40px;
    border: 0;
    background: none;
    box-shadow: 1px 0 0 rgba(255, 255, 255, 0.2), -1px 0 0 rgba(255, 255, 255, 0.2);
    z-index: 999;
}
.pkp_site_nav_toggle:focus {
    outline: 1px dotted rgba(0, 0, 0, 0.84);
    box-shadow: none;
}
.pkp_site_nav_toggle > span {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    width: 24px;
    height: 19px;
    border-bottom: 3px solid rgba(0, 0, 0, 0.84);
    text-indent: -9999px;
    overflow: hidden;
}
.pkp_site_nav_toggle > span:before,
.pkp_site_nav_toggle > span:after {
    content: "";
    position: absolute;
    left: 0;
    width: 100%;
    height: 3px;
    background: rgba(0, 0, 0, 0.84);
}
.pkp_site_nav_toggle > span:before {
    top: 0;
}
.pkp_site_nav_toggle > span:after {
    top: 8px;
}
.pkp_site_nav_toggle--transform > span {
    border-bottom: 0;
    overflow: visible;
}
.pkp_site_nav_toggle--transform > span:before {
    top: 7px;
    transform: rotate(-405deg) translateY(1px) translateX(-2px);
    -webkit-transform: rotate(-405deg) translateY(1px) translateX(-2px);
}
.pkp_site_nav_toggle--transform > span:after {
    top: 14px;
    transform: rotate(405deg) translateY(-3px) translateX(-4px);
    -webkit-transform: rotate(405deg) translateY(-3px) translateX(-4px);
}
.pkp_site_nav_menu {
    display: none;
}
.pkp_site_nav_menu--isOpen {
    display: block;
}
body.navIsOpen .siteHeader__details {
    right: 0;
}
body.navIsOpen .siteHeader__screen {
    display: block;
    opacity: 0.5;
}
body.navIsOpen .siteHeader__navToggleIcon > span:first-child {
    transform: rotate(45deg);
    top: 18px;
}
body.navIsOpen .siteHeader__navToggleIcon > span:nth-child(2) {
    opacity: 0;
}
body.navIsOpen .siteHeader__navToggleIcon > span:last-child {
    transform: rotate(-45deg);
    top: 18px;
}
@media (min-width: 992px) {
    .pkp_site_nav_menu {
        display: block;
    }
}
.pkp_search {
    position: relative;
    display: block;
    padding: 10px 0;
    font-size: 13px;
    line-height: 20px;
    text-align: left;
}
.pkp_search input[type="text"] {
    line-height: 34px;
    height: 34px;
    padding-right: 120px;
}
.pkp_search button[type="submit"] {
    position: absolute;
    top: 12px;
    right: 2px;
}
.pkp_search .search_controls {
    display: none;
    position: relative;
}
.pkp_search .search_controls a {
    text-decoration: none;
}
.pkp_search .search_prompt {
    transition: background-color 0.4s;
}
.pkp_search .search_prompt:before {
    display: inline-block;
    font: normal normal normal 14px/1 FontAwesome;
    font-size: inherit;
    text-rendering: auto;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    transform: translate(0, 0);
    content: "\f002";
    line-height: 18px;
}
.pkp_search .search_cancel,
.pkp_search .search_loading {
    display: none;
    position: absolute;
    top: 8px;
    right: 100%;
    margin-right: 20px;
    text-align: center;
    color: rgba(0, 0, 0, 0.54);
}
.pkp_search .search_cancel {
    width: 25px;
}
.pkp_search .search_cancel:before {
    display: inline-block;
    font: normal normal normal 14px/1 FontAwesome;
    font-size: inherit;
    text-rendering: auto;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    transform: translate(0, 0);
    content: "\f00d";
    width: 20px;
    height: 20px;
    line-height: 20px;
}
.pkp_search .search_cancel:hover,
.pkp_search .search_cancel:focus {
    outline: none;
    border-radius: 50%;
    background: #ff4040;
    color: #fff;
}
.pkp_search .search_loading {
    display: none;
}
.pkp_search .search_loading:after {
    display: inline-block;
    position: relative;
    width: 20px;
    height: 20px;
    vertical-align: middle;
    -webkit-animation: pkp_spin 0.6s linear infinite;
    -moz-animation: pkp_spin 0.6s linear infinite;
    -ms-animation: pkp_spin 0.6s linear infinite;
    -o-animation: pkp_spin 0.6s linear infinite;
    animation: pkp_spin 0.6s linear infinite;
    border-radius: 100%;
    border-top: 1px solid #888;
    border-bottom: 1px solid transparent;
    border-left: 1px solid #888;
    border-right: 1px solid transparent;
    border-top-color: rgba(0, 0, 0, 0.5);
    border-left-color: rgba(0, 0, 0, 0.5);
    content: "";
    opacity: 1;
}
.pkp_search_mobile {
    margin-top: 1rem;
    padding-bottom: 0;
    border-top: 1px solid rgba(255, 255, 255, 0.1);
}
.pkp_search_mobile .search_controls {
    display: none;
}
.pkp_search_desktop {
    display: none;
    float: right;
    padding: 5px 0;
    font-size: 13px;
    line-height: 20px;
    text-align: center;
}
@media (min-width: 480px) {
    .pkp_search input[type="text"] {
        line-height: 30px;
        height: 30px;
    }
    .pkp_search button[type="submit"] {
        position: relative;
        top: auto;
        right: auto;
    }
}
@media (min-width: 992px) {
    .pkp_search_mobile {
        display: none;
    }
    .pkp_search_desktop {
        display: block;
        position: absolute;
        top: 0;
        right: 0;
        height: 40px;
        min-width: 100px;
        padding: 0;
        font-size: 14px;
        line-height: 20px;
        transition: min-width 0.4s;
        text-align: right;
        overflow-x: hidden;
    }
    .pkp_search_desktop button {
        position: absolute;
        top: 0;
        left: -9999px;
    }
    .pkp_search_desktop input[type="text"] {
        position: absolute;
        top: 0;
        left: 0;
        width: 0;
        padding: 0;
        border: none;
    }
    .pkp_search_desktop .search_controls {
        display: inline-block;
    }
    .pkp_search_desktop .search_prompt {
        display: inline-block;
        position: relative;
        padding: 10px 20px;
        color: rgba(0, 0, 0, 0.84);
        cursor: pointer;
    }
    .pkp_search_desktop .search_prompt:before {
        font-size: 16px;
        margin-right: 0.25em;
    }
    .pkp_search_desktop .search_prompt:hover,
    .pkp_search_desktop .search_prompt:focus {
        outline: 0;
        padding-bottom: 8px;
        border-bottom: 2px solid rgba(0, 0, 0, 0.84);
    }
    .pkp_search_desktop.is_open {
        min-width: 100%;
        background: #fff;
    }
    .pkp_search_desktop.is_open input[type="text"] {
        width: 100%;
        max-width: 100%;
        line-height: 40px;
        height: 40px;
        top: 0;
        left: 0;
        padding-left: 0.5em;
        padding-right: 180px;
        border: none;
        border-bottom: 1px solid #ddd;
        font-size: 16px;
        background: #fff;
    }
    .pkp_search_desktop.is_open input[type="text"]:hover,
    .pkp_search_desktop.is_open input[type="text"]:focus {
        outline: 0;
    }
    .pkp_search_desktop.is_open .search_cancel {
        display: block;
    }
    .pkp_search_desktop.is_open .search_prompt {
        padding-bottom: 9px;
        background: #fff;
        border-left: 1px solid #ddd;
        border-bottom: 1px solid #ddd;
        color: #1b2c3d;
    }
    .pkp_search_desktop.is_open .search_prompt:hover,
    .pkp_search_desktop.is_open .search_prompt:focus {
        border-bottom-color: #1b2c3d;
    }
    .pkp_search_desktop.is_searching input[type="text"] {
        opacity: 0.5;
    }
    .pkp_search_desktop.is_searching input[type="text"]:hover,
    .pkp_search_desktop.is_searching input[type="text"]:focus {
        border-color: #fff;
    }
    .pkp_search_desktop.is_searching .search_prompt {
        background: #fff;
        border-left: 1px solid #ddd;
        color: #1b2c3d;
    }
    .pkp_search_desktop.is_searching .search_prompt:hover,
    .pkp_search_desktop.is_searching .search_prompt:focus {
        background: #fff;
        color: #900;
    }
    .pkp_search_desktop.is_searching .search_cancel {
        display: none;
    }
    .pkp_search_desktop.is_searching .search_loading {
        display: block;
    }
}
.pkp_page_index .journals {
    margin-top: 30px;
}
.pkp_page_index .journals > ul > li {
    margin: 30px 0;
}
.pkp_page_index .journals img {
    display: block;
    max-height: 20em;
}
.pkp_page_index .journals h3 {
    margin: 10px 0;
    font-size: 14px;
    font-weight: 700;
}
.pkp_page_index .journals h3 a {
    text-decoration: none;
}
.pkp_page_index .journals p {
    margin: 10px 0;
}
.pkp_page_index .journals .links li {
    display: inline-block;
    margin: 0 10px 10px 0;
}
@media (min-width: 768px) {
    .pkp_page_index .journals > ul > li {
        margin: 0 -20px;
        padding: 20px;
        border-top: 1px solid #ddd;
    }
    .pkp_page_index .journals > ul > li:before,
    .pkp_page_index .journals > ul > li:after {
        content: " ";
        display: table;
    }
    .pkp_page_index .journals > ul > li:after {
        clear: both;
    }
    .pkp_page_index .journals .thumb {
        float: left;
        width: 25%;
        padding-right: 20px;
    }
    .pkp_page_index .journals .thumb + .body {
        float: right;
        width: 75%;
    }
}
@media (min-width: 992px) {
    .pkp_page_index .journals > ul > li {
        margin: 0 -30px;
        padding: 30px;
    }
    .pkp_page_index .journals .thumb {
        padding-right: 30px;
    }
}
.pkp_page_index .homepage_image,
.pkp_page_index .additional_content {
    margin-left: -10px;
    margin-right: -10px;
}
@media (min-width: 480px) {
    .pkp_page_index .homepage_image,
    .pkp_page_index .additional_content {
        margin-left: -20px;
        margin-right: -20px;
    }
}
@media (min-width: 992px) {
    .pkp_page_index .homepage_image,
    .pkp_page_index .additional_content {
        margin-left: -30px;
        margin-right: -30px;
    }
}
.pkp_page_index .homepage_image img {
    display: block;
    width: 100%;
    height: auto;
}
@media (min-width: 992px) {
    .pkp_page_index .homepage_image {
        margin-top: -30px;
    }
}
.pkp_page_index .homepage_about {
    padding-top: 30px;
    padding-bottom: 30px;
}
.pkp_page_index .homepage_about h2 {
    margin-top: -10px;
}
.pkp_page_index .cmp_announcements {
    border-top: 1px solid #ddd;
    border-bottom: 1px solid #ddd;
}
.pkp_page_index .cmp_announcements:before,
.pkp_page_index .cmp_announcements:after {
    content: " ";
    display: table;
}
.pkp_page_index .cmp_announcements:after {
    clear: both;
}
.pkp_page_index .cmp_announcements > .obj_announcement_summary {
    position: relative;
    padding: 30px 10px;
}
.pkp_page_index .cmp_announcements .more {
    position: relative;
}
.pkp_page_index .cmp_announcements .more .obj_announcement_summary {
    padding: 10px;
}
.pkp_page_index .cmp_announcements .more h4 {
    font-size: 13px;
}
@media (min-width: 480px) {
    .pkp_page_index .cmp_announcements > .obj_announcement_summary,
    .pkp_page_index .cmp_announcements .more .obj_announcement_summary {
        padding-left: 20px;
        padding-right: 20px;
    }
}
@media (min-width: 768px) {
    .pkp_page_index .cmp_announcements > .obj_announcement_summary {
        float: left;
        width: 65%;
    }
    .pkp_page_index .cmp_announcements > .obj_announcement_summary:before {
        content: " ";
        position: absolute;
        top: 0;
        right: -1px;
        width: 1px;
        height: 100%;
        border-left: 1px solid #ddd;
    }
    .pkp_page_index .cmp_announcements .more {
        float: right;
        width: 35%;
        padding-top: 20px;
        padding-bottom: 20px;
    }
    .pkp_page_index .cmp_announcements .more:before {
        content: " ";
        position: absolute;
        top: 0;
        left: 0;
        width: 1px;
        height: 100%;
        border-left: 1px solid #ddd;
    }
}
@media (min-width: 992px) {
    .pkp_page_index .cmp_announcements > .obj_announcement_summary,
    .pkp_page_index .cmp_announcements .more .obj_announcement_summary {
        padding-left: 30px;
        padding-right: 30px;
    }
}
.pkp_page_index .current_issue .current_issue_title {
    margin: 20px 0;
    font-weight: 700;
}
.pkp_page_index .current_issue .read_more {
    display: inline-block;
    position: relative;
    padding-right: 30px;
    font-size: 13px;
    font-weight: 700;
    line-height: 30px;
    color: #1b2c3d;
    text-decoration: none;
    margin-bottom: 20px;
}
.pkp_page_index .current_issue .read_more:after {
    display: inline-block;
    font: normal normal normal 14px/1 FontAwesome;
    font-size: inherit;
    text-rendering: auto;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    transform: translate(0, 0);
    content: "\f054";
    position: absolute;
    top: 2px;
    right: 0;
    width: 30px;
    height: 30px;
    line-height: 30px;
    text-align: center;
}
.pkp_page_index .current_issue .read_more:hover,
.pkp_page_index .current_issue .read_more:focus {
    color: #900;
}
@media (min-width: 768px) {
    .pkp_page_index .current_issue .section:last-child {
        margin-bottom: 0;
    }
}
.pkp_page_index .additional_content {
    padding: 30px 10px 0 10px;
    border-top: 1px solid #ddd;
}
@media (min-width: 480px) {
    .pkp_page_index .additional_content {
        padding-left: 20px;
        padding-right: 20px;
    }
}
@media (min-width: 992px) {
    .pkp_page_index .additional_content {
        padding-left: 30px;
        padding-right: 30px;
    }
}
.pkp_page_index .additional_content > p:first-child {
    margin-top: 0;
}
.pkp_page_index .additional_content > p:last-child {
    margin-bottom: 0;
}
@media (min-width: 768px) {
    .pkp_page_index .cmp_announcements + .additional_content {
        border-top: none;
    }
}
.page_catalog_category .article_count {
    float: right;
    padding: 10px 0;
    font-size: 13px;
    color: rgba(0, 0, 0, 0.54);
}
.page_catalog_category .about_section .cover {
    float: right;
    width: 20%;
    margin-left: 10%;
    margin-right: 10%;
}
.page_catalog_category .subcategories li {
    padding-top: 5px;
    padding-bottom: 5px;
}
.page_catalog_category .subcategories a {
    text-decoration: none;
}
@media (min-width: 768px) {
    .page_catalog_category .subcategories {
        position: relative;
        margin-top: 60px;
        margin-left: -20px;
        margin-right: -20px;
        padding: 30px;
        border-top: 1px solid #ddd;
        border-bottom: 1px solid #ddd;
    }
    .page_catalog_category .subcategories h2 {
        position: absolute;
        top: -15px;
        left: 20px;
        margin: 0;
        padding-left: 10px;
        padding-right: 10px;
        line-height: 30px;
        background: #fff;
        color: rgba(0, 0, 0, 0.54);
    }
}
@media (min-width: 992px) {
    .page_catalog_category .subcategories {
        margin-left: -30px;
        margin-right: -30px;
    }
}
@media (min-width: 768px) {
    .page_catalog_category .cmp_article_list {
        padding-top: 20px;
    }
    .page_catalog_category h2.title {
        clip: rect(1px, 1px, 1px, 1px);
        position: absolute !important;
        left: -2000px;
    }
    .page_catalog_category h2.title:focus {
        background-color: #fff;
        border-radius: 3px;
        box-shadow: 0 0 2px 2px rgba(0, 0, 0, 0.6);
        -webkit-box-shadow: 0 0 2px 2px rgba(0, 0, 0, 0.6);
        clip: auto !important;
        color: #000;
        display: block;
        font-size: 14px;
        height: auto;
        line-height: normal;
        padding: 10px;
        position: absolute;
        left: 5px;
        top: 5px;
        text-decoration: none;
        width: auto;
        z-index: 100000;
    }
}
@media (min-width: 992px) {
    .page_catalog_category .cmp_article_list {
        padding-top: 30px;
    }
}
.page_contact .address,
.page_contact .phone,
.page_contact .email {
    margin-top: 10px;
    margin-bottom: 10px;
    font-size: 13px;
}
.page_contact .address {
    margin-top: 0;
}
.page_contact .address p {
    margin: 0;
}
.page_contact .label {
    display: block;
    font-weight: 700;
}
.page_contact .contact.support {
    margin-top: 40px;
}
@media (min-width: 768px) {
    .page_contact .contact_section:before,
    .page_contact .contact_section:after {
        content: " ";
        display: table;
    }
    .page_contact .contact_section:after {
        clear: both;
    }
    .page_contact .contact {
        float: left;
        width: 50%;
    }
    .page_contact .contact.primary {
        padding-right: 20px;
    }
    .page_contact .contact.support {
        margin-top: 0;
    }
}
.page_issue_archive .issues_archive {
    margin-left: -10px;
    margin-right: -10px;
    border-top: 1px solid #ddd;
}
.page_issue_archive .issues_archive > li {
    padding: 30px 10px;
    border-bottom: 1px solid #ddd;
}
@media (min-width: 480px) {
    .page_issue_archive .issues_archive {
        margin-left: -20px;
        margin-right: -20px;
    }
    .page_issue_archive .issues_archive > li {
        padding-left: 20px;
        padding-right: 20px;
    }
}
@media (min-width: 992px) {
    .page_issue_archive .issues_archive {
        margin-left: -30px;
        margin-right: -30px;
    }
    .page_issue_archive .issues_archive > li {
        padding-left: 30px;
        padding-right: 30px;
    }
}
.page_issue_archive .cmp_pagination {
    margin-top: 20px;
}
.page_login .login {
    margin-bottom: 0;
    max-width: 17em;
}
.page_login .login input[type="text"],
.page_login .login input[type="password"] {
    width: 100%;
}
.page_login .password a {
    font-size: 13px;
    font-style: normal;
}
.page_login .remember {
    padding-bottom: 0;
}
.page_login .remember .label {
    display: inline;
    font-style: normal;
}
.page_login .buttons button {
    float: right;
}
.page_login .buttons a {
    float: right;
    margin-right: 1em;
    margin-left: 0;
}
.page_lost_password .lost_password {
    margin-bottom: 0;
    max-width: 17em;
}
.page_lost_password .lost_password input[type="text"] {
    width: 100%;
}
.page_lost_password .pkp_form_error {
    margin: 20px 0;
    padding: 10px;
    background: #ff4040;
    color: #fff;
    font-size: 13px;
    font-weight: 700;
}
.page_lost_password .buttons:before,
.page_lost_password .buttons:after {
    content: " ";
    display: table;
}
.page_lost_password .buttons:after {
    clear: both;
}
.page_lost_password .buttons button {
    float: right;
}
.page_lost_password .buttons a {
    float: right;
    font-size: 13px;
    line-height: 30px;
    margin-right: 1em;
}
.page_register .required_label {
    font-size: 13px;
    line-height: 20px;
    color: rgba(0, 0, 0, 0.54);
    margin-bottom: 20px;
}
.page_register .consent {
    margin-bottom: 0;
}
.page_register .fields .reviewer_interests {
    max-height: 0;
    padding-bottom: 0;
    overflow: hidden;
    opacity: 0;
    transition: all 0.3s;
}
.page_register .fields .reviewer_interests.is_visible {
    max-height: 400px;
    overflow: visible;
    padding-bottom: 30px;
    opacity: 1;
}
.page_register .context_optin .contexts > li {
    margin-bottom: 1em;
}
.page_register .context_optin .contexts > li:last-child {
    margin-bottom: 0;
}
.page_register .context_optin .roles {
    padding: 5px 0;
    margin-bottom: 0;
}
.page_register .context_optin .roles label {
    display: inline-block;
    margin-right: 1em;
    font-size: 13px;
    line-height: 20px;
}
.page_register .context_optin .context_privacy {
    position: absolute;
    left: -9999px;
    padding: 5px 0;
    font-size: 13px;
    line-height: 20px;
}
.page_register .context_optin .context_privacy_visible {
    position: relative;
    left: auto;
}
.page_register #formErrors {
    margin: 20px 0;
    padding: 10px;
    background: #ff4040;
    color: #fff;
}
.page_register #formErrors .pkp_form_error {
    padding: 0px 0;
    font-size: 13px;
    font-weight: bold;
    line-height: 20px;
}
.page_register #formErrors .pkp_form_error_list {
    margin: 0;
    padding-left: 20px;
    font-size: 13px;
    line-height: 20px;
}
.page_register #formErrors .pkp_form_error_list a {
    color: #fff;
}
@media (min-width: 768px) {
    .page_register .identity li {
        display: inline-block;
        padding-right: 1em;
        max-width: 13em;
    }
}
@media (min-width: 1200px) {
    .page_register .identity li {
        max-width: 17em;
    }
}
.pkp_op_register .ui-helper-hidden-accessible {
    clip: rect(1px, 1px, 1px, 1px);
    position: absolute !important;
    left: -2000px;
}
.pkp_op_register .ui-helper-hidden-accessible:focus {
    background-color: #fff;
    border-radius: 3px;
    box-shadow: 0 0 2px 2px rgba(0, 0, 0, 0.6);
    -webkit-box-shadow: 0 0 2px 2px rgba(0, 0, 0, 0.6);
    clip: auto !important;
    color: #000;
    display: block;
    font-size: 14px;
    height: auto;
    line-height: normal;
    padding: 10px;
    position: absolute;
    left: 5px;
    top: 5px;
    text-decoration: none;
    width: auto;
    z-index: 100000;
}
.pkp_op_register .ui-autocomplete {
    position: absolute !important;
}
.page_search .search_input .query {
    width: 100%;
    max-width: 100%;
    height: 38px;
    font-size: 18px;
    line-height: 38px;
}
.page_search .search_advanced {
    border: 1px solid #ddd;
    padding: 0 20px 20px;
}
.page_search .search_advanced:before,
.page_search .search_advanced:after {
    content: " ";
    display: table;
}
.page_search .search_advanced:after {
    clear: both;
}
.page_search .search_advanced legend {
    padding: 10px 20px;
    margin: 0;
    font-weight: 400;
    color: rgba(0, 0, 0, 0.54);
}
.page_search .date_range {
    float: left;
    width: 50%;
}
.page_search .date_range .from {
    margin-bottom: 20px;
}
.page_search .date_range [name*="Year"] {
    width: 6em;
}
.page_search .date_range [name*="Day"] {
    width: 4em;
}
.page_search .date_range [name*="Month"] {
    width: 10em;
}
.page_search .author {
    width: 50%;
    float: right;
}
.page_search .submit {
    text-align: right;
}
.page_search .submit button {
    position: relative;
    padding-right: 45px;
    border-right: none;
    padding-right: 1em;
    padding-left: 45px;
    border-right: 1px solid rgba(0, 0, 0, 0.4);
    border-left: none;
}
.page_search .submit button:after {
    display: inline-block;
    font: normal normal normal 14px/1 FontAwesome;
    font-size: inherit;
    text-rendering: auto;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    transform: translate(0, 0);
    content: "\f002";
    position: absolute;
    top: -1px;
    right: 0;
    width: 30px;
    height: 30px;
    border-top-right-radius: 3px;
    border-bottom-right-radius: 3px;
    line-height: 30px;
    text-align: center;
    background: #1b2c3d;
    box-shadow: inset 0 -1em 1em rgba(0, 0, 0, 0.2);
    color: #fff;
}
.page_search .submit button:hover:after,
.page_search .submit button:focus:after {
    box-shadow: inset 0 1em 1em rgba(0, 0, 0, 0.2);
    background: #900;
}
.page_search .submit button:after {
    right: auto;
    left: 0;
    border-top-right-radius: 0;
    border-bottom-right-radius: 0;
    border-top-left-radius: 3px;
    border-bottom-left-radius: 3px;
}
.page_search .submit button:after {
    right: auto;
    left: 0;
}
.page_search .search_results {
    margin: 40px 0;
}
.page_search .search_results .obj_article_summary {
    padding: 20px 0;
}
.page_search .cmp_pagination {
    margin-top: 20px;
    font-size: 13px;
    line-height: 20px;
    color: rgba(0, 0, 0, 0.54);
    text-align: right;
}
.page_search .cmp_pagination a {
    padding-left: 0.5em;
    padding-right: 0.5em;
}
.page_section .section_description {
    margin-bottom: 2em;
}
.page_submissions .submission_sections ul,
.page_submissions .submission_checklist ul {
    margin: 20px 0 0;
    padding: 0;
    list-style: none;
    font-size: 13px;
    border: 1px solid #ddd;
    border-bottom: none;
}
.page_submissions .submission_sections li,
.page_submissions .submission_checklist li {
    position: relative;
    padding: 10px;
    border-bottom: 1px solid #ddd;
}
.page_submissions .submission_sections li:before,
.page_submissions .submission_checklist li:before {
    display: inline-block;
    font: normal normal normal 14px/1 FontAwesome;
    font-size: inherit;
    text-rendering: auto;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    transform: translate(0, 0);
}
.page_submissions .submission_sections h3 {
    margin-top: 0;
}
.page_submissions .submission_sections .cmp_notification {
    margin-bottom: 0;
}
@media (min-width: 480px) {
    .page_submissions .submission_sections li,
    .page_submissions .submission_checklist li {
        padding: 20px 20px 20px 40px;
    }
    .page_submissions .submission_sections li:before,
    .page_submissions .submission_checklist li:before {
        position: absolute;
        font-size: 18px;
        color: #00b24e;
    }
    .page_submissions .submission_sections li:before {
        content: "\f054";
        top: 22px;
        left: 17px;
    }
    .page_submissions .submission_checklist li:before {
        content: "\f00c";
        top: 50%;
        left: 20px;
        -webkit-transform: translate(-50%, -50%);
        -moz-transform: translate(-50%, -50%);
        -ms-transform: translate(-50%, -50%);
        -o-transform: translate(-50%, -50%);
        transform: translate(-50%, -50%);
    }
}
.header_view {
    z-index: 2;
    position: relative;
    background: #900;
}
.header_view a {
    line-height: 30px;
    text-decoration: none;
}
.header_view .return {
    position: absolute;
    top: 0;
    left: 0;
    width: 30px;
    height: 30px;
    line-height: 30px;
    background: #fff;
    color: #900;
    text-align: center;
}
.header_view .return:before {
    display: inline-block;
    font: normal normal normal 14px/1 FontAwesome;
    font-size: inherit;
    text-rendering: auto;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    transform: translate(0, 0);
    content: "\f060";
}
.header_view .return:hover,
.header_view .return:focus {
    background: #1b2c3d;
    color: #fff;
}
.header_view .title {
    display: block;
    padding-left: 40px;
    max-width: 100%;
    overflow-x: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;
    font-size: 13px;
    color: #fff;
}
.header_view .title:hover,
.header_view .title:focus {
    background: #1b2c3d;
}
.header_view .download {
    display: block;
    position: absolute;
    top: 0;
    right: 0;
    width: 30px;
    background: #fff;
    text-align: center;
}
.header_view .download:hover,
.header_view .download:focus {
    background: #1b2c3d;
    color: #fff;
}
.header_view .download:before {
    display: inline-block;
    font: normal normal normal 14px/1 FontAwesome;
    font-size: inherit;
    text-rendering: auto;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    transform: translate(0, 0);
    content: "\f019";
}
.header_view .download .label {
    display: none;
}
@media (min-width: 768px) {
    .header_view .title {
        font-size: 14px;
    }
    .header_view .download {
        width: auto;
        padding: 0 20px;
    }
    .header_view .download .label {
        display: inline-block;
    }
    .header_view .download .pkp_screen_reader,
    .header_view .download .pkp_page_index .cmp_announcements h2 {
        display: none;
    }
}
.galley_view {
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    overflow-y: hidden;
}
.galley_view iframe {
    width: 100%;
    height: 100%;
    padding-top: 30px;
    border: none;
}
.galley_view.galley_view_with_notice iframe {
    padding-top: 90px;
}
.galley_view .galley_view_notice {
    position: absolute;
    top: 30px;
    width: 100%;
    height: 60px;
    background: #ff4040;
}
.galley_view .galley_view_notice_message {
    position: absolute;
    top: 50%;
    left: 50%;
    width: 100%;
    transform: translate(-50%, -50%);
    color: rgba(0, 0, 0, 0.84);
    font-weight: 700;
    text-align: center;
}
.galley_view .galley_view_notice_message a {
    color: rgba(0, 0, 0, 0.84);
    text-decoration: underline;
}
.obj_announcement_full h1 {
    margin: 0;
}
.obj_announcement_full .date {
    margin: 16px 0;
    color: rgba(0, 0, 0, 0.54);
}
.obj_announcement_full .date:before {
    display: inline-block;
    font: normal normal normal 14px/1 FontAwesome;
    font-size: inherit;
    text-rendering: auto;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    transform: translate(0, 0);
    content: "\f073";
    margin-right: 0.5em;
    color: #ddd;
}
.obj_announcement_full .description {
    margin-top: 40px;
}
.obj_announcement_full .description p:first-child {
    margin-top: 0;
}
.obj_announcement_full .description p:last-child {
    margin-bottom: 0;
}
.obj_announcement_summary h2,
.obj_announcement_summary h3,
.obj_announcement_summary h4 {
    margin: 0;
    font-size: 14px;
    line-height: 20px;
}
.obj_announcement_summary h2 a,
.obj_announcement_summary h3 a,
.obj_announcement_summary h4 a {
    text-decoration: none;
}
.obj_announcement_summary .date {
    font-size: 13px;
    line-height: 25px;
    color: rgba(0, 0, 0, 0.54);
}
.obj_announcement_summary .date:before {
    display: inline-block;
    font: normal normal normal 14px/1 FontAwesome;
    font-size: inherit;
    text-rendering: auto;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    transform: translate(0, 0);
    content: "\f073";
    margin-right: 0.5em;
    font-size: 14px;
    color: #ddd;
}
.obj_announcement_summary .summary {
    font-size: 13px;
    line-height: 20px;
    margin-top: 10px;
}
.obj_announcement_summary .summary p:first-child {
    margin-top: 0;
}
.obj_announcement_summary .summary p:last-child {
    margin-bottom: 0;
}
.obj_announcement_summary .read_more {
    display: inline-block;
    position: relative;
    padding-right: 30px;
    font-size: 13px;
    font-weight: 700;
    line-height: 30px;
    color: #1b2c3d;
    text-decoration: none;
}
.obj_announcement_summary .read_more:after {
    display: inline-block;
    font: normal normal normal 14px/1 FontAwesome;
    font-size: inherit;
    text-rendering: auto;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    transform: translate(0, 0);
    content: "\f054";
    position: absolute;
    top: 2px;
    right: 0;
    width: 30px;
    height: 30px;
    line-height: 30px;
    text-align: center;
}
.obj_announcement_summary .read_more:hover,
.obj_announcement_summary .read_more:focus {
    color: #900;
}
.obj_article_details > .page_title {
    margin: 0;
}
.obj_article_details > .subtitle {
    margin: 0;
    font-size: 14px;
    line-height: 30px;
    font-weight: 400;
}
.obj_article_details .row {
    margin-top: 30px;
}
.obj_article_details .item {
    padding-top: 20px;
    padding-bottom: 20px;
}
.obj_article_details .item > *:first-child {
    margin-top: 0;
}
.obj_article_details .item > *:last-child {
    margin-bottom: 0;
}
.obj_article_details .sub_item {
    margin-bottom: 20px;
}
.obj_article_details .sub_item:last-child {
    margin-bottom: 0;
}
.obj_article_details .main_entry .item .label {
    margin: 0 0 20px;
    font-family: "Montserrat", -apple-system, BlinkMacSystemFont, "Segoe UI", "Roboto", "Oxygen-Sans", "Ubuntu", "Cantarell", "Helvetica Neue", sans-serif;
    font-size: 16px;
    font-weight: 700;
}
.obj_article_details .main_entry .sub_item .label {
    font-size: 14px;
}
.obj_article_details .authors li {
    margin-bottom: 10px;
}
.obj_article_details .authors .name {
    font-weight: bold;
    display: block;
}
.obj_article_details .authors .orcid {
    display: block;
    font-size: 12px;
    line-height: 20px;
}
.obj_article_details .authors .orcid a {
    vertical-align: middle;
}
.obj_article_details .authors .orcid_icon {
    width: 20px;
    height: 20px;
}
.obj_article_details .authors .affiliation {
    font-size: 13px;
    color: rgba(0, 0, 0, 0.54);
}
.obj_article_details .author_bios .sub_item .label {
    margin-bottom: 0;
}
.obj_article_details .author_bios .sub_item .value > p:first-child {
    margin-top: 0;
}
.obj_article_details .item.doi,
.obj_article_details .item.keywords {
    padding-top: 0;
}
.obj_article_details .galleys_links li {
    display: inline-block;
}
.obj_article_details .supplementary_galleys_links {
    margin-top: 10px;
}
.obj_article_details .copyright {
    font-size: 13px;
    line-height: 20px;
}
.obj_article_details .copyright a[rel="license"] + p {
    margin-top: 0;
}
.obj_article_details .entry_details {
    margin-left: -20px;
    margin-right: -20px;
    border-top: 1px solid #ddd;
}
.obj_article_details .entry_details .item {
    padding: 20px;
    border-bottom: 1px solid #ddd;
    word-wrap: break-word;
}
.obj_article_details .entry_details .item:last-child {
    border-bottom: none;
}
.obj_article_details .entry_details .item .label {
    margin: 0;
    font-family: "Montserrat", -apple-system, BlinkMacSystemFont, "Segoe UI", "Roboto", "Oxygen-Sans", "Ubuntu", "Cantarell", "Helvetica Neue", sans-serif;
    font-size: 13px;
    font-weight: 400;
    color: rgba(0, 0, 0, 0.54);
}
.obj_article_details .versions ul {
    margin: 0;
    padding: 0;
    list-style: none;
}
.obj_article_details .citation_display .value {
    font-size: 12px;
}
.obj_article_details .citation_display .csl-left-margin {
    display: none;
}
.obj_article_details .citation_display [aria-hidden="true"] {
    display: none;
}
.obj_article_details .citation_display .citation_formats {
    margin-top: 1em;
    border: 1px solid rgba(0, 0, 0, 0.4);
    border-radius: 3px;
}
.obj_article_details .citation_display .citation_formats_button {
    position: relative;
    background: transparent;
    border: none;
    border-bottom-left-radius: 0;
    border-bottom-right-radius: 0;
    box-shadow: none;
    padding: 0 1em;
    width: 100%;
    font-family: "Montserrat", -apple-system, BlinkMacSystemFont, "Segoe UI", "Roboto", "Oxygen-Sans", "Ubuntu", "Cantarell", "Helvetica Neue", sans-serif;
    font-weight: 400;
    color: rgba(0, 0, 0, 0.54);
    text-align: left;
}
.obj_article_details .citation_display .citation_formats_button:after {
    display: inline-block;
    font: normal normal normal 14px/1 FontAwesome;
    font-size: inherit;
    text-rendering: auto;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    transform: translate(0, 0);
    content: "\f0d7";
    position: absolute;
    top: 50%;
    right: 1em;
    transform: translateY(-50%);
}
.obj_article_details .citation_display .citation_formats_button[aria-expanded="true"]:after {
    content: "\f0d8";
}
.obj_article_details .citation_display .citation_formats_button:focus {
    background: #ddd;
    outline: 0;
}
.obj_article_details .citation_display .citation_formats_styles {
    margin: 0;
    padding: 0;
    list-style: none;
}
.obj_article_details .citation_display .citation_formats_styles a {
    display: block;
    padding: 0.5em 1em;
    border-bottom: 1px solid #ddd;
    text-decoration: none;
}
.obj_article_details .citation_display .citation_formats_styles a:focus {
    background: #ddd;
    outline: 0;
}
.obj_article_details .citation_display .citation_formats_styles li:last-child a {
    border-bottom: none;
}
.obj_article_details .citation_display .citation_formats_list .label {
    padding: 1em 1em 0.25em 1em;
}
.obj_article_details .citation_display .citation_formats_styles + .label {
    border-top: 1px solid #ddd;
}
.obj_article_details .citation_display span {
    margin-right: 0.5em;
}
@media (min-width: 480px) {
    .obj_article_details .entry_details {
        margin-left: -30px;
        margin-right: -30px;
    }
}
@media (min-width: 768px) {
    .obj_article_details .row {
        margin-left: -20px;
        margin-right: -20px;
        border-top: 1px solid #ddd;
        border-bottom: 1px solid #ddd;
    }
    .obj_article_details .main_entry {
        float: left;
        width: 428px;
        border-right: 1px solid #ddd;
    }
    .obj_article_details .item {
        padding: 20px;
    }
    .obj_article_details .item .label {
        margin: 0 0 20px;
        font-family: "Montserrat", -apple-system, BlinkMacSystemFont, "Segoe UI", "Roboto", "Oxygen-Sans", "Ubuntu", "Cantarell", "Helvetica Neue", sans-serif;
        font-size: 16px;
        font-weight: 700;
    }
    .obj_article_details .item.doi .label,
    .obj_article_details .item.keywords .label {
        display: inline;
        font-size: 14px;
    }
    .obj_article_details .entry_details {
        float: left;
        width: 300px;
        margin: 0 0 0 -1px;
        border-top: none;
        border-left: 1px solid #ddd;
    }
    .obj_article_details .entry_details .item {
        margin-right: -1px;
        border-bottom: 1px solid #ddd;
    }
    .obj_article_details .entry_details .item:last-child {
        border-bottom: none;
    }
}
@media (min-width: 992px) {
    .obj_article_details .row {
        margin-left: -30px;
        margin-right: -30px;
    }
    .obj_article_details .main_entry {
        width: 352px;
    }
    .obj_article_details .item {
        padding: 30px;
    }
}
@media (min-width: 1200px) {
    .obj_article_details .main_entry {
        width: 560px;
    }
}
.obj_article_summary:before,
.obj_article_summary:after {
    content: " ";
    display: table;
}
.obj_article_summary:after {
    clear: both;
}
.obj_article_summary .cover {
    display: block;
    margin-bottom: 20px;
}
.obj_article_summary .cover img {
    display: block;
    max-height: 250px;
    width: auto;
}
.obj_article_summary > .title {
    font-family: "Montserrat", -apple-system, BlinkMacSystemFont, "Segoe UI", "Roboto", "Oxygen-Sans", "Ubuntu", "Cantarell", "Helvetica Neue", sans-serif;
    font-size: 14px;
    line-height: 20px;
    font-weight: 700;
}
.obj_article_summary > .title a {
    text-decoration: none;
}
.obj_article_summary .subtitle {
    display: block;
    margin-top: 0.25em;
    margin-bottom: 0.5em;
    font-weight: 400;
    color: rgba(0, 0, 0, 0.54);
}
.obj_article_summary .meta {
    position: relative;
    padding-top: 5px;
    font-size: 13px;
    line-height: 20px;
}
.obj_article_summary .pages,
.obj_article_summary .published {
    color: rgba(0, 0, 0, 0.54);
}
.obj_article_summary .galleys_links {
    margin-top: 10px;
}
.obj_article_summary .galleys_links li {
    display: inline-block;
    margin-right: 1em;
}
.obj_article_summary .galleys_links li:last-child {
    margin-right: 0;
}
@media (min-width: 768px) {
    .obj_article_summary .authors {
        padding-right: 5em;
    }
    .obj_article_summary .pages {
        position: absolute;
        top: 0;
        right: 0;
        line-height: 30px;
    }
    .obj_article_summary .cover {
        float: left;
        width: 25%;
        height: auto;
        max-height: none;
        margin-right: 20px;
    }
}
@media (min-width: 992px) {
    .obj_article_summary .cover {
        margin-right: 30px;
        margin-bottom: 30px;
    }
    .obj_article_summary .cover img {
        max-height: none;
    }
}
.obj_galley_link:before {
    display: inline-block;
    font: normal normal normal 14px/1 FontAwesome;
    font-size: inherit;
    text-rendering: auto;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    transform: translate(0, 0);
    content: "\f0f6";
    margin-right: 0.25em;
}
.obj_galley_link.pdf:before {
    content: "\f1c1";
}
.obj_galley_link.restricted {
    border-color: #d00a6c;
    color: #d00a6c;
}
.obj_galley_link.restricted:before {
    display: inline-block;
    font: normal normal normal 14px/1 FontAwesome;
    font-size: inherit;
    text-rendering: auto;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    transform: translate(0, 0);
    content: "\f023";
    color: #d00a6c;
}
.obj_galley_link.restricted:hover,
.obj_galley_link.restricted:focus {
    background: #d00a6c;
    color: #fff;
}
.obj_galley_link.restricted:hover:before,
.obj_galley_link.restricted:focus:before {
    color: #fff;
}
.obj_galley_link_supplementary {
    display: inline-block;
    position: relative;
    padding-right: 30px;
    font-size: 13px;
    font-weight: 700;
    line-height: 30px;
    color: #1b2c3d;
    text-decoration: none;
    padding-right: 0;
    padding-left: 20px;
}
.obj_galley_link_supplementary:after {
    display: inline-block;
    font: normal normal normal 14px/1 FontAwesome;
    font-size: inherit;
    text-rendering: auto;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    transform: translate(0, 0);
    content: "\f0f6";
    position: absolute;
    top: 2px;
    right: 0;
    width: 30px;
    height: 30px;
    line-height: 30px;
    text-align: center;
}
.obj_galley_link_supplementary:hover,
.obj_galley_link_supplementary:focus {
    color: #900;
}
.obj_galley_link_supplementary:after {
    right: auto;
    left: 0;
    text-align: left;
}
.obj_issue_summary h2 {
    margin: 0;
    font-size: 14px;
    line-height: 20px;
    font-weight: 400;
}
.obj_issue_summary .cover {
    display: block;
    margin-bottom: 20px;
}
.obj_issue_summary .cover img {
    display: block;
    width: auto;
    max-height: 250px;
}
.obj_issue_summary .title {
    font-family: "Montserrat", -apple-system, BlinkMacSystemFont, "Segoe UI", "Roboto", "Oxygen-Sans", "Ubuntu", "Cantarell", "Helvetica Neue", sans-serif;
    font-weight: 700;
    text-decoration: none;
}
.obj_issue_summary .series {
    margin-bottom: 5px;
    color: rgba(0, 0, 0, 0.54);
}
.obj_issue_summary .description {
    font-size: 13px;
    line-height: 20px;
}
.obj_issue_summary .description p:first-child {
    margin-top: 0;
}
.obj_issue_summary .description p:last-child {
    margin-bottom: 0;
}
@media (min-width: 768px) {
    .obj_issue_summary:before,
    .obj_issue_summary:after {
        content: " ";
        display: table;
    }
    .obj_issue_summary:after {
        clear: both;
    }
    .obj_issue_summary .cover {
        float: left;
        width: 25%;
        height: auto;
        margin-right: 20px;
    }
    .obj_issue_summary .cover img {
        max-height: auto;
    }
}
.obj_issue_toc h3 {
    display: inline-block;
    margin-top: 40px;
    border-bottom: 2px solid rgba(0, 0, 0, 0.87);
    font-size: 14px;
    line-height: 18px;
}
.obj_issue_toc .cover {
    display: block;
    margin-bottom: 20px;
}
.obj_issue_toc .cover img {
    display: block;
    max-height: 250px;
    width: auto;
}
.obj_issue_toc .description > *:first-child {
    margin-top: 0;
}
.obj_issue_toc .description > *:last-child {
    margin-bottom: 0;
}
.obj_issue_toc .pub_id {
    margin: 20px 0;
}
.obj_issue_toc .pub_id .type {
    font-weight: 700;
}
.obj_issue_toc .published {
    margin: 20px 0;
}
.obj_issue_toc .published .label {
    font-weight: 700;
}
.obj_issue_toc .sections:not(:first-child) {
    margin-top: 60px;
}
.obj_issue_toc .section:last-child .articles > li:last-child {
    margin-bottom: 0;
}
.obj_issue_toc .galleys_links {
    margin-top: 10px;
}
.obj_issue_toc .galleys_links li {
    display: inline-block;
    margin-right: 1em;
}
.obj_issue_toc .galleys_links li:last-child {
    margin-right: 0;
}
@media (min-width: 768px) {
    .obj_issue_toc .heading:before,
    .obj_issue_toc .heading:after {
        content: " ";
        display: table;
    }
    .obj_issue_toc .heading:after {
        clear: both;
    }
    .obj_issue_toc .cover {
        float: left;
        width: 25%;
        height: auto;
        max-height: none;
        margin-right: 20px;
    }
    .obj_issue_toc .galleys,
    .obj_issue_toc .section {
        position: relative;
        margin: 30px -20px;
        padding: 30px;
    }
    .obj_issue_toc .galleys:before,
    .obj_issue_toc .section:before {
        content: "";
        position: absolute;
        top: 45px;
        left: 0;
        width: 100%;
        border-top: 1px solid #ddd;
    }
    .obj_issue_toc .galleys h2,
    .obj_issue_toc .section h2 {
        display: inline-block;
        position: relative;
        left: -15px;
        margin-top: 0;
        padding: 0 15px;
        background: #fff;
        font-size: 16px;
        font-weight: 400;
        color: rgba(0, 0, 0, 0.54);
    }
}
@media (min-width: 992px) {
    .obj_issue_toc .galleys,
    .obj_issue_toc .section {
        margin: 30px -30px;
    }
    .obj_issue_toc .cover {
        margin-right: 30px;
        margin-bottom: 30px;
    }
    .obj_issue_toc .cover img {
        max-height: none;
    }
}
.pkp_block {
    padding: 30px 20px;
    font-size: 14px;
    line-height: 20px;
}
.pkp_block .title {
    display: block;
    margin-bottom: 10px;
    font-family: "Montserrat", -apple-system, BlinkMacSystemFont, "Segoe UI", "Roboto", "Oxygen-Sans", "Ubuntu", "Cantarell", "Helvetica Neue", sans-serif;
    font-size: 16px;
    font-weight: 700;
    line-height: 20px;
    color: rgba(0, 0, 0, 0.54);
}
.pkp_block .content ul li {
    line-height: 20px;
    padding: 5px 0;
}
.pkp_block .content p {
    line-height: 25px;
}
.pkp_block .content p:first-child {
    margin-top: 0;
}
.pkp_block .content p:last-child {
    margin-bottom: 0;
}
.pkp_block a {
    text-decoration: none;
}
@media (min-width: 992px) {
    .pkp_block {
        padding: 30px;
    }
}
.block_browse {
    font-size: 13px;
}
.block_browse .has_submenu {
    margin-top: 20px;
    font-size: 13px;
    font-weight: 700;
    color: rgba(0, 0, 0, 0.54);
}
.block_browse .has_submenu ul {
    margin-top: 4px;
    padding-top: 5px;
    font-weight: 400;
}
.block_browse .is_sub {
    margin-left: 10px;
}
.block_browse .current a {
    padding-left: 0.5em;
    border-left: 4px solid #ddd;
    color: rgba(0, 0, 0, 0.54);
    cursor: text;
}
.block_information a,
.block_language_toggle a {
    font-size: 13px;
}
.block_subscription .subscription_name {
    margin-bottom: 0;
    font-weight: 700;
}
.block_subscription .subscription_membership {
    margin-top: 0;
}
.pkp_structure_footer_wrapper {
    background: #ddd;
}
.pkp_structure_footer {
    text-align: center;
}
.pkp_footer_content {
    padding: 30px;
    text-align: left;
}
.pkp_brand_footer {
    padding: 30px;
}
.pkp_brand_footer:before,
.pkp_brand_footer:after {
    content: " ";
    display: table;
}
.pkp_brand_footer:after {
    clear: both;
}
.pkp_brand_footer a {
    float: right;
    display: block;
    max-width: 150px;
}
body[dir="rtl"] {
    direction: rtl;
    unicode-bidi: embed;
}
@media (min-width: 768px) {
    body[dir="rtl"] .pkp_structure_main:before {
        left: auto;
        right: 0;
    }
    body[dir="rtl"] .pkp_structure_main:after {
        left: auto;
        right: 728px;
    }
}
@media (min-width: 992px) {
    body[dir="rtl"] .pkp_structure_main {
        float: right;
    }
    body[dir="rtl"] .pkp_structure_main:after {
        left: auto;
        right: 652px;
    }
    body[dir="rtl"] .pkp_structure_sidebar {
        float: left;
    }
}
@media (min-width: 1200px) {
    body[dir="rtl"] .pkp_structure_main:after {
        left: auto;
        right: 860px;
    }
}
@media (min-width: 992px) {
    body[dir="rtl"] .pkp_site_name {
        text-align: right;
    }
}
body[dir="rtl"] .pkp_navigation_primary ul {
    text-align: right;
}
body[dir="rtl"] .pkp_navigation_user {
    text-align: left;
}
body[dir="rtl"] .pkp_navigation_user li {
    text-align: right;
}
body[dir="rtl"] .pkp_head_wrapper .pkp_search {
    right: auto;
    left: 0;
    text-align: left;
}
body[dir="rtl"] .pkp_head_wrapper .pkp_search.is_open .search_prompt {
    border-left: none;
    border-right: 1px solid #ddd;
}
body[dir="rtl"] .pkp_head_wrapper .pkp_search.is_open input[type="text"] {
    padding-right: 0.5em;
    padding-left: 180px;
}
body[dir="rtl"] .pkp_screen_reader,
body[dir="rtl"] .cmp_skip_to_content a,
body[dir="rtl"] .pkp_page_index .journals h2,
body[dir="rtl"] .pkp_page_index .cmp_announcements h2,
body[dir="rtl"] .page_register .context_optin .roles legend,
body[dir="rtl"] .pkp_page_index .cmp_announcements h2 {
    left: auto;
    right: -2000px;
}
body[dir="rtl"] .pkp_screen_reader:focus,
body[dir="rtl"] .cmp_skip_to_content a:focus,
body[dir="rtl"] .pkp_page_index .journals h2:focus,
body[dir="rtl"] .pkp_page_index .cmp_announcements h2:focus,
body[dir="rtl"] .page_register .context_optin .roles legend:focus,
body[dir="rtl"] .pkp_page_index .cmp_announcements h2:focus {
    right: 50%;
}
body[dir="rtl"] .obj_announcement_summary .date:before {
    margin-right: 0;
    margin-left: 0.5em;
}
body[dir="rtl"] .obj_issue_toc .galleys_links li {
    margin-right: inherit;
    margin-left: 1em;
}
@media (min-width: 768px) {
    body[dir="rtl"] .obj_issue_toc .galleys h2,
    body[dir="rtl"] .obj_issue_toc .section h2 {
        left: auto;
        right: 15px;
    }
    body[dir="rtl"] .obj_issue_toc .cover {
        float: right;
        margin-right: inherit;
        margin-left: 20px;
    }
}
@media (min-width: 992px) {
    body[dir="rtl"] .obj_issue_toc .cover {
        margin-right: inherit;
        margin-left: 30px;
    }
}
@media (min-width: 768px) {
    body[dir="rtl"] .obj_issue_summary .cover {
        float: right;
        margin-right: inherit;
        margin-left: 20px;
    }
}
@media (min-width: 768px) {
    body[dir="rtl"] .obj_article_summary {
        padding-right: 0;
        padding-left: 5em;
    }
}
@media (min-width: 768px) {
    body[dir="rtl"] .galleys h2,
    body[dir="rtl"] .section h2 {
        left: auto;
        right: 15px;
    }
    body[dir="rtl"] .cover {
        float: right;
        margin-right: inherit;
        margin-left: 20px;
    }
}
@media (min-width: 992px) {
    body[dir="rtl"] .cover {
        margin-right: inherit;
        margin-left: 30px;
    }
}
body {
    background: #ddd;
}
.pkp_structure_page {
    margin: 0 auto;
    max-width: 1160px;
    background: #fff;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}
@media (min-width: 1200px) {
    .pkp_structure_page {
        margin-top: 30px;
        margin-bottom: 30px;
    }
}
.pkp_structure_footer_wrapper {
    background: rgba(0, 0, 0, 0.05);
    border-top: 1px solid #ddd;
    border-bottom: 20px solid #d4d7d9;
}
.pkp_structure_main:before,
.pkp_structure_main:after {
    display: none;
}
.pkp_structure_content {
    padding-top: 0;
}
@media (min-width: 992px) {
    .pkp_structure_sidebar:before {
        content: "";
        position: absolute;
        top: 0;
        right: 0;
        bottom: 0;
        width: 300px;
        border-left: 1px solid #ddd;
    }
    .pkp_structure_sidebar > * {
        position: relative;
    }
}
@media (min-width: 992px) {
    .pkp_structure_main:first-child:last-child {
        float: none;
        margin-left: auto;
        margin-right: auto;
        margin-top: 40px;
    }
    .pkp_structure_main:first-child:last-child:before {
        left: 150px;
    }
    .pkp_structure_main:first-child:last-child:after {
        left: auto;
        right: 150px;
    }
}
.cmp_manuscript_button,
.block_make_submission a,
.obj_galley_link {
    font-family: "Montserrat", -apple-system, BlinkMacSystemFont, "Segoe UI", "Roboto", "Oxygen-Sans", "Ubuntu", "Cantarell", "Helvetica Neue", sans-serif;
    font-weight: 700;
    text-transform: uppercase;
    background: #d4d7d9;
    color: rgba(0, 0, 0, 0.84);
    border: none;
}
.cmp_manuscript_button:hover,
.cmp_manuscript_button:focus,
.block_make_submission a:hover,
.block_make_submission a:focus,
.obj_galley_link:hover,
.obj_galley_link:focus {
    background: #d4d7d9;
}
.cmp_breadcrumbs {
    padding: 30px 0;
    font-family: "Montserrat", -apple-system, BlinkMacSystemFont, "Segoe UI", "Roboto", "Oxygen-Sans", "Ubuntu", "Cantarell", "Helvetica Neue", sans-serif;
    font-size: 13px;
    color: rgba(0, 0, 0, 0.54);
    text-transform: uppercase;
}
.cmp_breadcrumbs > ol {
    padding: 0;
    margin: 0;
}
.cmp_breadcrumbs .current {
    text-transform: none;
}
.cmp_breadcrumbs .current h1 {
    font-family: "Montserrat", -apple-system, BlinkMacSystemFont, "Segoe UI", "Roboto", "Oxygen-Sans", "Ubuntu", "Cantarell", "Helvetica Neue", sans-serif;
}
.cmp_breadcrumbs .separator {
    padding: 0 0.1em;
    opacity: 0.3;
}
.cmp_pagination {
    font-family: "Montserrat", -apple-system, BlinkMacSystemFont, "Segoe UI", "Roboto", "Oxygen-Sans", "Ubuntu", "Cantarell", "Helvetica Neue", sans-serif;
}
.cmp_pagination a {
    font-weight: 700;
    text-transform: uppercase;
}
.cmp_pagination .prev:before {
    content: "\f053";
}
.cmp_pagination .next:after {
    content: "\f054";
}
.cmp_announcements {
    border: none;
}
.cmp_announcements > li {
    border-bottom: none;
}
.cmp_announcements .obj_announcement_summary h2,
.cmp_announcements .obj_announcement_summary h3,
.cmp_announcements .obj_announcement_summary h4,
.cmp_announcements .date,
.cmp_announcements .read_more {
    font-family: "Montserrat", -apple-system, BlinkMacSystemFont, "Segoe UI", "Roboto", "Oxygen-Sans", "Ubuntu", "Cantarell", "Helvetica Neue", sans-serif;
    font-size: 13px;
    font-weight: 700;
}
.cmp_announcements .read_more {
    text-transform: uppercase;
}
.cmp_announcements .date {
    font-weight: 400;
}
.cmp_announcements .date:before {
    color: #d4d7d9;
}
.pkp_head_wrapper,
.has_site_logo .pkp_head_wrapper {
    position: relative;
    padding-top: 0;
}
.pkp_site_name_wrapper {
    padding-left: 30px;
    padding-right: 30px;
}
.pkp_site_name .is_text {
    font-size: 14px;
    text-transform: uppercase;
}
@media (min-width: 992px) {
    .pkp_site_name {
        width: 75%;
        margin-left: 0;
        padding-top: 15px;
        padding-bottom: 15px;
    }
    .pkp_site_name .is_text {
        font-size: 18px;
    }
}
@media (min-width: 992px) {
    .pkp_navigation_primary_row {
        background: #fff;
        padding-left: 30px;
        padding-right: 30px;
    }
}
.pkp_navigation_primary_wrapper {
    width: auto;
}
#navigationPrimary a {
    font-family: "Montserrat", -apple-system, BlinkMacSystemFont, "Segoe UI", "Roboto", "Oxygen-Sans", "Ubuntu", "Cantarell", "Helvetica Neue", sans-serif;
    font-size: 13px;
    font-weight: 700;
    text-transform: uppercase;
}
#navigationPrimary > li > a {
    padding-bottom: 6px;
    border-bottom-width: 4px;
}
#navigationPrimary > li > a:hover,
#navigationPrimary > li > a:focus {
    border-color: #d4d7d9;
}
#navigationPrimary > [aria-haspopup] > a:hover,
#navigationPrimary > [aria-haspopup] > a:focus {
    border-color: transparent;
}
#navigationPrimary [aria-expanded="true"]:before {
    border-bottom-color: #d4d7d9;
}
@media (min-width: 992px) {
    #navigationPrimary a {
        color: rgba(0, 0, 0, 0.54);
    }
    #navigationPrimary a:hover,
    #navigationPrimary a:focus {
        color: #d4d7d9;
    }
    #navigationPrimary ul {
        background: #d4d7d9;
    }
    #navigationPrimary ul a {
        color: rgba(0, 0, 0, 0.84);
    }
    #navigationPrimary ul a:hover,
    #navigationPrimary ul a:focus {
        border-color: transparent;
    }
}
.pkp_head_wrapper .pkp_search .search_controls .search_prompt {
    padding-bottom: 10px;
    border-bottom: none;
    font-family: "Montserrat", -apple-system, BlinkMacSystemFont, "Segoe UI", "Roboto", "Oxygen-Sans", "Ubuntu", "Cantarell", "Helvetica Neue", sans-serif;
    font-size: 13px;
    color: rgba(0, 0, 0, 0.54);
    font-weight: 700;
    text-transform: uppercase;
}
.pkp_head_wrapper .pkp_search .search_controls .search_prompt:hover,
.pkp_head_wrapper .pkp_search .search_controls .search_prompt:focus {
    color: #1b2c3d;
}
.pkp_head_wrapper .pkp_search .search_controls .search_prompt:before {
    color: #d4d7d9;
}
.pkp_head_wrapper .pkp_search .search_controls .search_prompt:before:hover,
.pkp_head_wrapper .pkp_search .search_controls .search_prompt:before:focus {
    color: #d4d7d9;
}
.pkp_head_wrapper .pkp_search.is_open {
    min-width: 50%;
}
.pkp_head_wrapper .pkp_search.is_open input[type="text"] {
    border-bottom: none;
    background: rgba(0, 0, 0, 0.05);
    border-left: 1px solid #ddd;
}
.pkp_head_wrapper .pkp_search.is_open .search_controls .search_prompt {
    background: #d4d7d9;
    color: rgba(0, 0, 0, 0.84);
}
.pkp_head_wrapper .pkp_search.is_open .search_controls .search_prompt:hover,
.pkp_head_wrapper .pkp_search.is_open .search_controls .search_prompt:focus {
    border-bottom: transparent;
}
.pkp_head_wrapper .pkp_search.is_open .search_controls .search_prompt:before {
    color: rgba(0, 0, 0, 0.84);
}
.pkp_navigation_user_wrapper a {
    font-family: "Montserrat", -apple-system, BlinkMacSystemFont, "Segoe UI", "Roboto", "Oxygen-Sans", "Ubuntu", "Cantarell", "Helvetica Neue", sans-serif;
    font-size: 13px;
    font-weight: 700;
}
@media (min-width: 992px) {
    .pkp_navigation_user_wrapper {
        top: 13px;
        right: 0;
        left: auto;
        width: 25%;
        transform: none;
        padding-right: 30px;
    }
    .pkp_navigation_user_wrapper a {
        color: rgba(0, 0, 0, 0.54);
    }
    .pkp_navigation_user_wrapper ul a:hover,
    .pkp_navigation_user_wrapper ul a:focus {
        border-color: #d4d7d9;
    }
    .pkp_navigation_user_wrapper .pkp_navigation_user {
        margin-right: 0;
        padding-right: 0;
        width: auto;
    }
}
.pkp_block .title {
    display: inline-block;
    padding-bottom: 0.5em;
    border-bottom: 3px solid #d4d7d9;
    font-weight: 700;
    text-transform: uppercase;
}
.pkp_page_index .homepage_image {
    margin-top: -1px;
}
.pkp_page_index .cmp_announcements {
    border: none;
}
@media (min-width: 768px) {
    .pkp_page_index .cmp_announcements > .more:before,
    .pkp_page_index .cmp_announcements > .obj_announcement_summary:before {
        display: none;
    }
}
@media (min-width: 992px) {
    .pkp_page_index .cmp_announcements h2 + .obj_announcement_summary,
    .pkp_page_index .cmp_announcements .more {
        padding-top: 80px;
        padding-bottom: 80px;
    }
    .pkp_page_index .cmp_announcements .more .obj_announcement_summary {
        padding-top: 0;
        padding-bottom: 0;
        margin-bottom: 20px;
    }
    .pkp_page_index .cmp_announcements .more .obj_announcement_summary:last-child {
        margin-bottom: 0;
    }
}
@media (min-width: 1200px) {
    .pkp_page_index .cmp_announcements {
        border-bottom: 1px solid #ddd;
    }
    .pkp_page_index .cmp_announcements > .more:before,
    .pkp_page_index .cmp_announcements > .obj_announcement_summary:before {
        display: block;
    }
}
.pkp_page_index .current_issue h2 {
    display: inline-block;
    padding-bottom: 0.5em;
    border-bottom: 3px solid #d4d7d9;
    text-transform: uppercase;
    font-weight: 700;
    color: rgba(0, 0, 0, 0.54);
}
.pkp_page_index .current_issue .current_issue_title {
    font-family: "Montserrat", -apple-system, BlinkMacSystemFont, "Segoe UI", "Roboto", "Oxygen-Sans", "Ubuntu", "Cantarell", "Helvetica Neue", sans-serif;
    font-size: 16px;
}
.pkp_page_index .current_issue .sections {
    margin-top: 20px;
}
.pkp_page_index .current_issue .read_more {
    font-family: "Montserrat", -apple-system, BlinkMacSystemFont, "Segoe UI", "Roboto", "Oxygen-Sans", "Ubuntu", "Cantarell", "Helvetica Neue", sans-serif;
    font-weight: 700;
    text-transform: uppercase;
}
.pkp_structure_main:first-child:last-child .cmp_announcements {
    border-bottom: none;
}
.pkp_structure_main:first-child:last-child .cmp_announcements > .more:before,
.pkp_structure_main:first-child:last-child .cmp_announcements > .obj_announcement_summary:before {
    display: none;
}
.pkp_structure_main:first-child:last-child .additional_content {
    border-top: none;
}
.page_announcement {
    margin-top: 30px;
}
.page_issue_archive .issues_archive,
.page_issue_archive .issues_archive > li {
    border: none;
}
.page_search .search_advanced {
    margin-top: 10px;
}
.page_search .search_advanced legend {
    font-family: "Montserrat", -apple-system, BlinkMacSystemFont, "Segoe UI", "Roboto", "Oxygen-Sans", "Ubuntu", "Cantarell", "Helvetica Neue", sans-serif;
    font-size: 13px;
    font-weight: 700;
    text-transform: uppercase;
}
.header_view {
    background: #d4d7d9;
    color: rgba(0, 0, 0, 0.84);
}
.header_view .title {
    color: rgba(0, 0, 0, 0.84);
}
.header_view .title:hover,
.header_view .title:focus {
    background: #d4d7d9;
    color: rgba(0, 0, 0, 0.84);
    text-decoration: underline;
}
.obj_issue_toc .heading .pub_id,
.obj_issue_toc .heading .published {
    font-family: "Montserrat", -apple-system, BlinkMacSystemFont, "Segoe UI", "Roboto", "Oxygen-Sans", "Ubuntu", "Cantarell", "Helvetica Neue", sans-serif;
    font-size: 13px;
}
.obj_issue_toc .heading .pub_id .type,
.obj_issue_toc .heading .published .label {
    font-weight: 700;
    color: rgba(0, 0, 0, 0.54);
    text-transform: uppercase;
}
.obj_issue_toc .heading .pub_id .id,
.obj_issue_toc .heading .published .value {
    margin-left: 0.5em;
}
.obj_issue_toc .heading .pub_id .id a {
    color: rgba(0, 0, 0, 0.87);
    text-decoration: none;
}
.obj_issue_toc .heading .pub_id .id a:hover,
.obj_issue_toc .heading .pub_id .id a:focus {
    color: #900;
    text-decoration: underline;
}
.obj_issue_toc > .galleys,
.obj_issue_toc .section {
    margin: 0;
    padding: 0;
    border: none;
}
.obj_issue_toc > .galleys:before,
.obj_issue_toc .section:before {
    display: none;
}
.obj_issue_toc > .galleys h2,
.obj_issue_toc .section h2 {
    position: relative;
    display: inline-block;
    top: auto;
    left: auto;
    padding: 0 0 5px;
    border-bottom: 3px solid #d4d7d9;
    background: transparent;
    text-transform: uppercase;
    font-weight: 700;
}
.obj_issue_toc .galleys_links li {
    margin-bottom: 0.5em;
}
.obj_issue_toc .pages {
    font-family: "Montserrat", -apple-system, BlinkMacSystemFont, "Segoe UI", "Roboto", "Oxygen-Sans", "Ubuntu", "Cantarell", "Helvetica Neue", sans-serif;
}
.obj_issue_toc .cover img {
    margin-left: auto;
    margin-right: auto;
}
.obj_issue_summary .series {
    font-family: "Montserrat", -apple-system, BlinkMacSystemFont, "Segoe UI", "Roboto", "Oxygen-Sans", "Ubuntu", "Cantarell", "Helvetica Neue", sans-serif;
}
.obj_galley_link.restricted {
    border-color: #ddd;
    background: #ddd;
    color: rgba(0, 0, 0, 0.54);
}
.obj_galley_link.restricted:before {
    color: rgba(0, 0, 0, 0.54);
}
.obj_galley_link.restricted:hover,
.obj_galley_link.restricted:focus {
    background: rgba(0, 0, 0, 0.54);
}
.obj_article_summary .subtitle {
    font-family: "Montserrat", "Noto Serif", -apple-system, BlinkMacSystemFont, "Segoe UI", "Roboto", "Oxygen-Sans", "Ubuntu", "Cantarell", "Helvetica Neue", sans-serif;
    font-size: 13px;
}
.obj_article_details .subtitle {
    font-family: "Montserrat", "Noto Serif", -apple-system, BlinkMacSystemFont, "Segoe UI", "Roboto", "Oxygen-Sans", "Ubuntu", "Cantarell", "Helvetica Neue", sans-serif;
}
.obj_article_details .authors,
.obj_article_details .doi {
    font-family: "Montserrat", -apple-system, BlinkMacSystemFont, "Segoe UI", "Roboto", "Oxygen-Sans", "Ubuntu", "Cantarell", "Helvetica Neue", sans-serif;
}
.obj_article_details .orcid a,
.obj_article_details .doi a {
    color: rgba(0, 0, 0, 0.87);
    text-decoration: none;
}
.obj_article_details .orcid a:hover,
.obj_article_details .doi a:hover,
.obj_article_details .orcid a:focus,
.obj_article_details .doi a:focus {
    color: #1b2c3d;
    text-decoration: underline;
}
.obj_article_details .orcid a {
    font-size: 10px;
    color: rgba(0, 0, 0, 0.54);
}
.obj_article_details .authors li {
    margin-bottom: 20px;
}
.obj_article_details .main_entry .label {
    display: inline-block;
    padding: 0 0 5px;
    border-bottom: 3px solid #d4d7d9;
    color: rgba(0, 0, 0, 0.54);
    text-transform: uppercase;
}
.obj_article_details .main_entry .doi .label,
.obj_article_details .main_entry .keywords .label {
    display: inline;
    padding: 0;
    border: none;
    text-transform: none;
}
.obj_article_details .row,
.obj_article_details .main_entry,
.obj_article_details .entry_details {
    border: none;
}
.obj_article_details .author_bios .sub_item .label {
    border-bottom: none;
    text-transform: none;
}
.obj_article_details .entry_details {
    margin-left: 0;
    margin-right: 0;
}
.obj_article_details .entry_details .label {
    font-weight: 700;
    text-transform: uppercase;
}
.obj_article_details .entry_details .item {
    margin: 30px 0;
    padding: 0;
    border-bottom: none;
    border-radius: 3px;
    background: rgba(0, 0, 0, 0.05);
    box-shadow: 0 0 1px rgba(0, 0, 0, 0.4);
}
.obj_article_details .entry_details .item .label + .value {
    border-top-left-radius: 0;
    border-top-right-radius: 0;
}
.obj_article_details .entry_details .sub_item {
    padding: 0;
    margin-bottom: 0;
}
.obj_article_details .entry_details .sub_item:last-child {
    margin-bottom: 0;
}
.obj_article_details .entry_details .sub_item .label {
    color: rgba(0, 0, 0, 0.54);
}
.obj_article_details .entry_details .item > .label,
.obj_article_details .entry_details .sub_item:first-child > .label {
    padding: 0.5em 20px;
    background: #ddd;
    border-top-left-radius: 3px;
    border-top-right-radius: 3px;
}
.obj_article_details .entry_details .item > .value,
.obj_article_details .entry_details .sub_item .value {
    padding: 20px;
    border-radius: 3px;
}
.obj_article_details .entry_details .sub_item:not(:first-child) .label {
    display: inline-block;
    padding: 0.5em 0;
    margin: 0 20px;
    border-bottom: 3px solid #d4d7d9;
}
.obj_article_details .entry_details .cover_image {
    background: transparent;
    box-shadow: none;
}
.obj_article_details .entry_details .cover_image img {
    display: block;
    border-radius: 3px;
    margin-left: auto;
    margin-right: auto;
}
.obj_article_details .entry_details .item.galleys {
    box-shadow: none;
}
.obj_article_details .entry_details .item.galleys .galleys_links {
    padding: 0;
}
.obj_article_details .entry_details .galleys_links > li {
    display: block;
    margin-bottom: 0.5em;
}
.obj_article_details .entry_details .galleys_links > li:last-child {
    margin-bottom: 0;
}
.obj_article_details .entry_details .galleys_links > li a {
    display: block;
}
.obj_article_details .entry_details .citation_display {
    margin-bottom: 0;
}
.obj_article_details .entry_details .item.copyright {
    box-shadow: none;
}
@media (min-width: 768px) {
    .obj_article_details .entry_details {
        width: 240px;
        margin-left: 30px;
    }
}

@charset "UTF-8";
/* CSS Document */

/**************************Global Body Variables*******************************/

a {
	color:#101e5a;
	text-decoration:none;
}

a:hover {
	color:#3366cc;
	text-decoration:underline;
}

body {
background-image: linear-gradient(297deg, transparent 0%, transparent 34%,rgba(178,178,178, 0.02) 34%, rgba(178,178,178, 0.02) 53%,transparent 53%, transparent 100%),linear-gradient(222deg, transparent 0%, transparent 30%,rgba(202,216,243, 0.24) 30%, rgba(202,216,243, 0.24) 58%,transparent 58%, transparent 100%),linear-gradient(352deg, transparent 0%, transparent 25%,rgba(204,217,247, 0.11) 25%, rgba(204,217,247, 0.11) 57%,transparent 57%, transparent 100%),linear-gradient(90deg, rgb(255,255,255),rgb(255,255,255));}

.pkp_structure_page {
	margin:0 auto;
	background:transparent;
	box-shadow:none;
}
.carousel-inner{
	position:absolute;
}
/***************************************************************************/

.aimcolumn {
  float: left;
 
}

.aimleft {
  width: 25%;
  padding-top:10px;
  padding-left:10px;
}

.aimright {

  width: 74%;
  height:auto;
  padding: 0px 20px 0px 35px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}
.row{
	margin-right:0;
	margin-left:0;
}
@media screen and (max-width: 600px) {
  .aimcolumn {
    width: 100%;
  }
  .aimleft {
  	padding-top: 10px;
	width:250px;

	
}
}




/**************************cover image*************************************/

.obj_issue_toc .cover {
	display:none;
}

/**************************COPE block*************************************/
.cope { 
    width:25%; 
    margin-left: auto;
  margin-right: auto;
    } 

/**************************Submission block*************************************/

.cmp_manuscript_button, .block_make_submission a, .obj_galley_link{
	background-color:#101e5a;
	color:white;
	text-align:center;
	text-decoration: none;
	box-shadow: 5px 7px 9px -4px rgb(158, 158, 158);
}
.block_make_submission a{
width: 100%;
}
ul.galleys_links li {
font-family: "Montserrat", "Noto Serif", -apple-system, BlinkMacSystemFont, "Segoe UI", "Roboto", "Oxygen-Sans", "Ubuntu", "Cantarell", "Helvetica Neue", sans-serif;
}
/**************************MENU HEADER*************************************/

#navigationPrimary>li>a{
	color:#101e5a;
}
.pkp_head_wrapper .pkp_search .search_controls .search_prompt{
	color:#101e5a;
}
.pkp_nav_list li.profile {
    padding: 0px 8px 2px 5px;
    border: 1px solid #e6dfdf;
    border-right: 1px solid #dadada;
    border-bottom: 1px solid #dadada;
    border-radius: 8px;
    font-size: 16px;
    box-shadow: 3px 2px 5px -2px rgba(0,0,0,.2);
    margin-left: 8px;
    margin-right:5px;
}
.pkp_navigation_user>li>a{
	color:whitesmoke;
}
.pkp_navigation_primary_row{
background-image: repeating-radial-gradient(circle at center center, transparent 0px, transparent 2px,rgba(74,137,220, 0.09) 2px, rgba(74,137,220, 0.09) 3px,transparent 3px, transparent 5px,rgba(74,137,220, 0.09) 5px, rgba(74,137,220, 0.09) 7px),repeating-radial-gradient(circle at center center, rgb(255,255,255) 0px, rgb(255,255,255) 9px,rgb(255,255,255) 9px, rgb(255,255,255) 21px,rgb(255,255,255) 21px, rgb(255,255,255) 31px,rgb(255,255,255) 31px, rgb(255,255,255) 40px); background-size: 20px 20px;	

	padding-top:5px;
	padding-bottom:5px;
}
#navigationPrimary ul a{
	color:#101e5a;
}

#navigationPrimary ul a:hover{
	background-color:whitesmoke;
	color:#3e82da;
}

#navigationPrimary > li > a:hover {
	color:#4A89DC;
}





/**************************MENU SEARCH*************************************/


/**************************HEADER*************************************************/
.pkp_structure_head { 
  position: relative; 
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color:#042d59f7;
  margin-bottom:.25em;

}

.pkp_structure_head::before {
      content: "";
      background: url(https://malang-post.com/wp-content/uploads/2020/11/tambak-udang.jpg) #36c no-repeat;
      background-size: cover;
      position: absolute;
      top: 0px;
      right: 0px;
      bottom: 0px;
      left: 0px;
      opacity: 20%;
      box-shadow: inset 8px 3px 20px 1px rgba(0, 0, 0, 0.75);
  }


.pkp_structure_page {
    max-width: 100%;
    margin-top: 0;
    margin-bottom: 0;
}

.pkp_site_name_wrapper {
    padding-left: 30px;
    padding-right: 30px;
    margin: 0px;
}
.pkp_site_name .is_img img{
	margin-top:30px;
	margin-bottom:20px;
	max-height:150px;

}

/**************************BREADCRUMBS********************************************/

.cmp_breadcrumbs {
	padding:1.3em 0.5em;
	font-family:'Source Sans Pro', sans-serif;
	font-weight:400;
	font-size:12px;
	color:rgba(0, 0, 0, 0.54);
	text-transform:uppercase;
	
	border-bottom:1px solid #ececec;
	width:100%;
}


/**************************MAIN SITE**********************************************/

.pkp_page_index .homepage_image img {
	display:block;
	width:100%;
	height:auto;
	border-top-left-radius:20px;
	border-top-right-radius:20px;
}

.pkp_page_index .additional_content {
	border-top:0px solid #ddd;
	padding: 10px 0px 0px 3px;
}

.pkp_structure_content {
	font-size:15px;
	margin-bottom:.3em;
	-webkit-box-shadow: 0px 0px 5px 0.5px rgba(103,104,107,0.34);
-moz-box-shadow: 0px 0px 5px 0.5px rgba(103,104,107,0.34);
box-shadow: 0px 0px 5px 0.5px rgba(103,104,107,0.34);


}

.pkp_structure_main {
	background-color:transparent;
	border-radius:20px;
	-moz-border-radius:20px;
	-webkit-border-radius:20px;

}

/**************************ISSUES ARCHIVE*****************************************/

.obj_issue_summary {
	margin:0em 3em 0em 1.6em;
	padding-left:1em;
	border-left:1px solid #101e5a;
}

.obj_issue_summary .cover {
	display:none;
}

.page_issue_archive .issues_archive > li {
	margin:0em 0em 0em 0em;
	padding:2em 0em 0em 0.7em;
}

/**************************ARTICLES SUMMARY***************************************/

.obj_issue_toc .sections:not(:first-child) {
	margin-top:0em;
}

.obj_issue_toc .section > h2 {
	border-bottom:0px;
	border-left:0px;
	font-family:'Source Sans Pro', sans-serif;
	font-weight:300;
	text-transform:capitalize;
	padding:0.15em 1em;
	background-color:#fafbfb;
	width:100%;	
	border-radius:20px;
	-moz-border-radius:20px;
	-webkit-border-radius:20px;
    box-shadow: 0 1px 3px rgba(0,0,0,0.12), 0 1px 2px rgba(0,0,0,0.24);

}

ul.galleys_links {
	list-style:none;
}

.obj_article_summary {
	padding:0em 1.5em;
}

.obj_article_summary .cover {
	display:block;
	float:left;
	width:70px;
	height:auto;
	margin-right:15px;
}

.obj_article_summary > .title {
	font-family:'Source Sans Pro', sans-serif;
	font-weight:400;
	font-size:15px;
	text-transform:capitalize;

}

.obj_article_summary > .title a {
	display:block;
	text-decoration:none;
	font-size:16px;
	color:#333
}

.doi_summary {
	/*width:66%;
	background-color:#fafbfb;
	border-radius:4px; 
	-moz-border-radius:4px;
	-webkit-border-radius:4px;*/
	
	padding:0.4em 0.7em;
	margin-top:0.3em;
}

.doi_summary a {
	text-decoration:none !important;
}

.doi_summary a:hover {
	text-decoration:underline !important;
}

.obj_article_summary > .galleys_links {
	/*float:left;
	text-align:left;
	width:100%;*/
	list-style:none;
	margin-bottom:0.5em;
}
.obj_article_summary > .galleys_links a {
	color:#fff;
	background-color:#101e5a;
}

.obj_article_summary > .galleys_links a:hover {
	background-color:#3366cc;
	text-decoration:none;
}


/**************************ARTICLES DETAILS***************************************/

.obj_article_details > .page_title {
	font-weight:600;
}

.obj_article_details .doi a {
	color:#101e5a;
	font-family:'Source Sans Pro', sans-serif;
}

.obj_article_details .doi a:hover {
	color:#3366cc;
	font-family:'Source Sans Pro', sans-serif;
}

.obj_article_details .entry_details .item.galleys .galleys_links {
   padding:0;
   background-color:#fff;
}

.obj_article_details .entry_details .item.galleys .galleys_links a {
	color:#fff;
	background-color:#101e5a;
}

.obj_article_details .entry_details .item.galleys .galleys_links a:hover {
	background-color:#3366cc;
}

.obj_article_details .entry_details .sub_item:not(:first-child) .label {
   display:inline-block;
   padding:.5em 0;
   margin:0 20px;
   width:83%;
   border-bottom:1px solid #101e5a;
}

.obj_article_details .entry_details .item > .value ul {
	list-style:none;
	padding:0;
	margin:0;
}

.obj_article_details .entry_details .item > .value ul li {
	padding:5px 0;
}

.obj_article_details .main_entry .label {
	border-bottom:0px;
	border-left:0px;	
	font-weight:300;
	text-transform:capitalize;
	width:100%;	
	border-radius:15px;
	-moz-border-radius:15px;
	-webkit-border-radius:15px;
}

.obj_article_details .item {
	padding:1em 0em 2em 2.5em;
}

.obj_article_details .main_entry .item .label {
	font-size:16px;
}

.obj_article_details .galleys_links a:hover {
	background-color:#3366cc;
	text-decoration:none;
}

.obj_article_details .entry_details .cover_image img {
	width:200px
}

/**************************SIDER BAR**********************************************/

.pkp_structure_sidebar:before {
	border-left:0px solid #ddd;
}

.pkp_block {
	padding: 0px 3px 5px 5px;
	font-size:14px;
	line-height:20px;
}
.block_make_submission{
padding: 15px 3px 5px 5px;
}

.pkp_block .title {
	width:100%;
	background-color:#101e5a;
	height:30px;
	font-size:13px;
	color:#ecececec;
	padding-top:0.4em;
	margin-bottom:0px;
	border:0px;
	text-align:center;
	
	font-family:'Source Sans Pro', sans-serif;
}

.pkp_block .content {
	background-color:#4A89DC;

}

.pkp_block .content ul li {
	padding:0px 0;
	background-color:#4A89DC;
}

.pkp_block li {
   border-radius:0;
   position:relative;
   background-color:#f1f1f1;
   display:block;
}

.pkp_block ul>li {
	border-bottom:1px solid rgba(0,0,0,.125);
}

.pkp_block ul>li a {
	color:white;
	padding:.75rem 1rem;
   display:flex;
}

.pkp_block ul>li a:hover {
   text-decoration:none;
   background-color:#3e82da;
}



/**************************Announcement block*************************************************/

.block_announcements_article{
	padding:1em 1em 1em;
	background-color:#3e82da;
	color:whitesmoke;
}
/**************************FOOTER*************************************************/

.pkp_structure_footer_wrapper {
	border-top:none;
	font-size:15px;
	border-bottom:10px solid #101e5a;
}

.pkp_footer_content a {
	color:#090909;
	text-decoration:none;
}

.pkp_footer_content a:hover {
	color:#3366cc;
	text-decoration:none;
}



/**************************MEDIA*************************************************/

/* Tablet in modalitÃ  verticale */
@media all and (min-width:376px) and (max-width:990px) {
	.pkp_structure_main {
		padding:0px 10px 10px 10px;
		overflow:auto;
		margin-bottom:1.5em;
	}

	.obj_article_details .item {
		padding:2em 0.5em 0em 1.5em;
	}
	.pkp_block {
		padding:0px 0px 20px 0px;
		font-size:14px;
		line-height:20px;
	}
	.pkp_site_nav_toggle {
            position: absolute;
            right: 0;
            top: 5%;
            width: 4em;
            margin-top: -5em;
}
.carousel-inner{
	position:relative;
}

.pkp_site_name .is_img img{
	max-height:90px;
	margin-top:-5px

}
.has_site_logo .pkp_site_name, .has_site_logo .pkp_navigation_primary_wrapper{
	text-align:center;
	left:0;
	padding-left:0px;
}
.pkp_navigation_user>li>a{
	color:#101e5a;
}
.pkp_site_nav_menu{
top:-65%;
}
.pkp_site_nav_menu a{
	color:#101e5a;
}
.pkp_nav_list li.profile {
    margin-left: 8px;
    margin-right:25px;
    text-align:center;
    margin-bottom:5px;
}
.pkp_structure_head { 
height:25vh;
}
}

/* Smartphone o piccoli Tablet */
@media all and (max-width:376px) {
	
	.pkp_structure_main {
		padding:0px 10px 10px 10px;
		overflow:auto;
		margin-bottom:1.5em;
	}

	.pkp_block {
		padding:0px 0px 20px 0px;
		font-size:14px;
		line-height:20px;
	}
	.pkp_footer_content {
		width:100%;
		float:none;
	}
	.pkp_site_nav_toggle {
            position: absolute;
            right: 0;
            top: 5%;
            width: 4em;
            margin-top: -5em;
}	.pkp_structure_main {
		padding:0px 10px 10px 10px;
		overflow:auto;
		margin-bottom:1.5em;
	}

	.obj_article_details .item {
		padding:2em 0.5em 0em 0.5em;
	}

.carousel-inner{
	position:relative;
}

.pkp_site_name .is_img img{
	max-height:60px;
	margin-top:-5px

}
.has_site_logo .pkp_site_name, .has_site_logo .pkp_navigation_primary_wrapper{
	text-align:center;
	left:5px;
}
.has_site_logo .pkp_site_name, .has_site_logo .pkp_navigation_primary_wrapper{
	text-align:center;
	padding:0px;
}
.pkp_navigation_user>li>a{
	color:#101e5a;
}
.pkp_site_nav_menu{
top:-65%;
}
.pkp_site_nav_menu a{
	color:#101e5a;
}
.pkp_structure_head { 
height:25vh;
}
}

/**********************
/***** Services *******
/*********************/
@import url('https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css');
section{
	padding: 20px 0;
}
section .section-title{
	text-align:center;
	color:#101e5a;
	margin-bottom:50px;
	text-transform:uppercase;
}
#what-we-do{
	background:transparent;
}
#what-we-do .card{
	padding: 1rem!important;
	border: none;
	margin-bottom:1rem;
	-webkit-transition: .5s all ease;
	-moz-transition: .5s all ease;
	transition: .5s all ease;
	background-image: radial-gradient(circle at 28% 29%, rgba(237, 237, 237,0.04) 0%, rgba(237, 237, 237,0.04) 50%,rgba(136, 136, 136,0.04) 50%, rgba(136, 136, 136,0.04) 100%),radial-gradient(circle at 8% 78%, rgba(156, 156, 156,0.04) 0%, rgba(156, 156, 156,0.04) 50%,rgba(37, 37, 37,0.04) 50%, rgba(37, 37, 37,0.04) 100%),radial-gradient(circle at 29% 46%, rgba(251, 251, 251,0.04) 0%, rgba(251, 251, 251,0.04) 50%,rgb(244,249,254) 50%, rgb(244,249,254) 100%),linear-gradient(90deg, rgb(216,225,243),rgb(216,225,243));
	box-shadow: 0 1px 3px rgba(0,0,0,0.12), 0 1px 2px rgba(0,0,0,0.24);
}
#what-we-do .card:hover{
	-webkit-box-shadow: 5px 7px 9px -4px rgb(158, 158, 158);
	-moz-box-shadow: 5px 7px 9px -4px rgb(158, 158, 158);
	box-shadow: 5px 7px 9px -4px rgb(158, 158, 158);
}
#what-we-do .card .card-block{
	padding-left: 50px;
    position: relative;
}
#what-we-do .card .card-block a{
	color: #101e5a !important;
	font-weight:700;
	text-decoration:none;
}
#what-we-do .card .card-block a i{
	display:none;
	
}
#what-we-do .card:hover .card-block a i{
	display:inline-block;
	font-weight:700;
	
}
#what-we-do .card .card-block:before{
	font-family: FontAwesome;
    position: absolute;
    font-size: 39px;
    color: #101e5a;
    left: 0;
	-webkit-transition: -webkit-transform .2s ease-in-out;
    transition:transform .2s ease-in-out;
}
#what-we-do .card .block-1:before{
    content: "\f25e";
}
#what-we-do .card .block-2:before{
    content: "\f0eb";
}
#what-we-do .card .block-3:before{
    content: "\f00c";
}
#what-we-do .card .block-4:before{
    content: "\f155";
}

#what-we-do .card:hover .card-block:before{
	-webkit-transform: rotate(360deg);
	transform: rotate(360deg);	
	-webkit-transition: .5s all ease;
	-moz-transition: .5s all ease;
	transition: .5s all ease;
}
#what-we-do .card-title{
	margin: auto;
}

.container-fluid{
	padding-left:0px;
	padding-right:0px;
}

.carousel-indicators {
  bottom:-15px;
}

/**********************
/***** Tabs *******
/*********************/
nav > .nav.nav-tabs{

  border: none;
    color:#101e5a;
    background:#f1f1f1;
    border-radius:0;

}
nav > div a.nav-item.nav-link,
nav > div a.nav-item.nav-link.active
{
  border: none;
  padding: 18px 25px;
  font-weight:bold;
  color:whitesmoke;
  background: #4A89DC;
  border-radius:0;
}

nav > div a.nav-item.nav-link.active:after
 {
  content: "";
  position: relative;
  bottom: -60px;
  left: -10%;
}
.tab-content{
  background: #e9ecefb8;
  line-height: 25px;
  border-bottom:1px solid #e9ecef;
  padding: 10px 10px 10px 10px;
  box-shadow: 0 1px 3px rgba(0,0,0,0.12), 0 1px 2px rgba(0,0,0,0.24);
}

nav > div a.nav-item.nav-link:hover,
nav > div a.nav-item.nav-link:focus
{
  border: none;
  background: #e9ecef;
  color: #101e5a;
  border-radius:none;
  transition:background 0.20s linear;
}
.c-no{height:150px;}
.grey-bg{background:#4A89DC;}
.counter-Txt{color:whitesmoke; text-align:center; font-size:20px; text-transform:uppercase; margin-top:20px;}
.counter-Txt span{display:block; font-size:36px}
@media(min-width:320px) and (max-width:767px){ 
.c-no{height:100%;}
.counter-Txt{margin-top:35px;}
.margin-bot-35{margin-bottom:35px;}
}
@media (min-width: 350px) {
   .container {
    max-width: 1200px;
  }
}

/**********************
/***** Most viewed plugin heading *******
/*********************/
.most-viewed-headline{
  border-bottom: 3px solid #101e5a;
}

/**********************
/***** Footer Columns *******
/*********************/
* {
  box-sizing: border-box;
}
footerbody {
  margin: 0;
}
/* Create four equal columns that floats next to each other */
.footercolumn {
  float: left;
  width: 25%;
  padding: 15px;
}
/* Clear floats after the columns */
.footerrow:after {
  content: "";
  display: table;
  clear: both;
}
/* Responsive layout - makes the three columns stack on top of each other instead of next to each other */
@media screen and (max-width:600px) {
  .footercolumn {
    width: 100%;
  }
}
/********************************
/***** Social Media Icons *******
/********************************/
.social:hover {
     -webkit-transform: scale(1.1);
     -moz-transform: scale(1.1);
     -o-transform: scale(1.1);
 }
 .social {
     -webkit-transform: scale(0.8);
     /* Browser Variations: */
     
     -moz-transform: scale(0.8);
     -o-transform: scale(0.8);
     -webkit-transition-duration: 0.5s;
     -moz-transition-duration: 0.5s;
     -o-transition-duration: 0.5s;
 }

/*
    Multicoloured Hover Variations
*/
#social-fb{
    color:darkgray;
}
 
 #social-tw{
    color:darkgray;
}
#social-gp{
    color:darkgray;
}
#social-em{
    color:darkgray;
}
 #social-fb:hover {
     color: #3B5998;
 }
 #social-tw:hover {
     color: #4099FF;
 }
 #social-gp:hover {
     color: #d34836;
 }
 #social-em:hover {
     color: #f39c12;
 }
 .fa{color:#101e5a;
 }

/**********************
/***** Brand footer *******
/*********************/
.pkp_brand_footer 
{display:none;
}

/**********************
/***** Tables *******
/*********************/
table {
  font-family: arial, sans-serif;
  border-collapse: collapse;
  width: 100%;
}

td, th {
  border: 1px solid #dddddd;
  text-align: left;
  padding: 8px;
}

tr:nth-child(even) {
  background-color: #dddddd;
}
/************************************
/***** Article detail page *******
/***********************************/
.obj_article_details .page_title {
    text-align: left;
}

.obj_article_details>.subtitle {
   text-align: left;
}

.obj_article_details .item.doi {
    	text-align: left;
	text-decoration: none;
}

.obj_article_details .item.keywords {
    text-transform: capitalize;
}

.item.abstract{
	text-align: justify;
	padding-top: 0px;
}
