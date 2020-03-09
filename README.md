
# Better-object-embed

Better-object-embed is a module that allows you to make embed objects more easily. It is used to transform a builder into an object.Better-object-embed doesn't use discord.js.
## Installation



```
npm i --s better-object-embed
```

## Example

```js
const BetterObjectEmbed = require("better-object-embed") // require better-object-embed.
const Embed = new BetterObjectEmbed()

.setTitle("A title")
.setDescription("A beautiful description")
.setColor("RED")
.addField("name","value",inline) //inline must be true or false
.addBlankField()
.setAuthor("name","icon","url")
.attachFiles(file)
.setImage("url")
.setThumbnail("url")
.setFooter("name","icon")
.setTimestamp(Date.now())
message.channel.send({embed: Embed.build})
```
