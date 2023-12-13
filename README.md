# Deprecation Notice
This extension with be merging with the official PlatformOS extension for vscode over the coming months. The new extension can be found here https://marketplace.visualstudio.com/items?itemName=platformOS.platformos-check-vscode 
The idea is to deprecate the first one to have one official platformOS extension to avoid confusion. Before doing it, we'd like to understand who's using this extension and what features should be transferred into the new one before moving forward with the deprecation.
If you have any requests for features to be transferred please go to the new extension and make a request there.

# platformOS - VS Code extension
This extension adds: 
1. Liquid markup Syntax Highlighting and supports Liquid Theme Tag
2. Snippets for Liquid, YAML, grahpQL & marketplace-kit terminal.

Visual Studio Marketplace link: [https://marketplace.visualstudio.com/items?itemName=digitalfuel.vscode-platformOS](https://marketplace.visualstudio.com/items?itemName=digitalfuel.vscode-platformOS)

<!-- ## Preview (currently unavailable)
![Showcase](./images/showcase.gif) -->

## Requirements
1. Install the latest Visual Studio Code
<!-- ## Dependencies -->

This extension is available for free in the [Visual Studio Code Marketplace](https://marketplace.visualstudio.com)

## Installation
1. Launch VS Code
2. From the command palette `Ctrl`-`Shift`-`X` (Windows, Linux) or `Cmd`-`Shift`-`X` (OSX)
3. Search `platformOS`
4. Click to install
5. Configure File Association for '.liquid' to `HTML pos-liquid` from the **Change Language Mode** `(Ctrl+K M)`, when a `.liquid` file is in focus.

## Emmet Enable
Go to user settings and add the following:
```
"emmet.includeLanguages": { "liquid": "html" },
"files.associations": {
        "*.liquid": "liquid"
    },
```

## Usage
Type part of a snippet, press `Enter`, and the snippet unfolds.

Alternatively, press `Ctrl`+`Space` (Windows, Linux) or `Cmd`+`Space` (OSX) to activate snippets from within the editor.

## Tip
Using `Tab` and disabling `Enter` for accepting suggestions can avoid ambiguity between inserting new lines or accepting the suggestions. 
**Settings** `"editor.acceptSuggestionOnEnter": "off"`

#### Liquid
Whitespace control is add for all snippets. And can be removed when needed by deleting the - inside liquid tags.

## Terminal ( ?: )

### Marketplace-kit
```javascript
Install/Update
Test (show version)
Initialize
Add environment
List environments
Deploy
Deploy with force
Sync
GUI
```

## YAML ( ---: )

### Preferences
```javascript
Page
Metadata
Response Headers
user_profile_types
transactable_types
order_types
custom_model_types
notifications email, SMS , API
authorization_policies
form_configurations
    - default_payload
    - validation
    - translations
```

## Liquid ( {%:, {{:, |:, %: )

### Comment Tag
```javascript
comment
```

### Control Flow Tag
```javascript
if
else
elsif
ifelse
unless
case
when
```

### Iteration Tag
```javascript
cycle
cyclegroup
for
limit       // For loops option
offset      // For loops option
reversed    // For loops option
break
continue
tablerow
```

### Variable Tag
```javascript
assign
increment
decrement
capture
```

### Theme Tag
```javascript
liquid
render
include // deprecated
includewith    // Theme Tag {% include %} with parameters
includefor    // Theme Tag {% include %} with parameters
raw
```

### Array Filter
```javascript
join
first
last
concat
map
reverse
size
sort
uniq
```

### Math Filter
```javascript
abs
ceil
divided_by
floor
minus
plus
round
times
modulo
```

### Money Filter
```javascript
To Come
```

### String Filter
```javascript
append
camelcase
captialize
downcase
escape
handleize
md5
newline_to_br
pluralize
prepend
remove
remove_first
replace
replace_first
slice
slice_single   // String Filter 'slice' with single parameter
split
strip
lstrip
rstrip
strip_html
strip_newlines
truncate
truncatewords
upcase
url_encode
url_escape
url_param_escape
```

## GraphQL ( gql )

### Example snippets
```javascript
Search page content
```

## Console.log ( clog )

### Example snippets
```javascript
Form Builder
```

## Release

### 0.0.5
- platform-OS - Use at your own risk

## License
MIT
