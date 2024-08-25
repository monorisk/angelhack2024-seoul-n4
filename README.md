# GARBAGE COLLECT (angelhack2024-seoul Team-N4)

### What is GC
With location-based services, "The area I live in" gets clean.

### Why People Use GC
The experience of being free from environmental pollution shows that environmental improvement is not difficult.<br>
This is a service that everyone can participate in.<br>
I don’t do it alone, anyone can report and collect trash.<br>
It is cute and fun service.<br>
It can be used lightly in everyday life as if it were a Pokémon!<br>

### Maintainer
- Sunghoon Park (monorisk@gmail.com)
- Jeongeun Lee (sweetzhzh@gmail.com)
- Seungjoo Jeong (lovelyyy902@gmail.com)
- Siyoon Jung (siyoon.syj@gmail.com)


## Link

- APP: https://github.com/monorisk/angelhackathon2024-seoul-n4-app
- SERVER: https://github.com/seungjoopet/angelhack
- FE: https://github.com/chbin05/hackseoul2024

## Demo Video

- Youtube: https://www.youtube.com/watch?v=ffuGBZAv2tM

<br>
<br>
<br>

### [FE] Get Started
#### build
```
yarn build
```

#### start
```
yarn start
```

<br>
<br>

### [SERVER] Get Started
#### Build
```
gradlew build
gradlew jar
```
#### Run
```
java -jar ${jarFileName}.jar
```
<br>
<br>

### [APP (For Android)] Get Started
#### Local Run with Expo Go
```
yarn start
```

#### Expo App Build
```
eas build -p android --profile preview
```

<br>
<br>
<br>

## Test Guide
1. Build the FE
2. Input results files of #1 to the SERVER project. (/resources/static/)
3. Build and execute the SERVER
4. Build the APP & install on your Android Device
