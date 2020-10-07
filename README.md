## Config

### Usage of Config

```java
//create config
Config config = new Config(/* Path of file */);

//set value
config.set(/* key */, /* value */);

//set value if not exists in config
config.add(/* key */, /* value */);

//save config
config.save();

//reload file content
config.reload();
```