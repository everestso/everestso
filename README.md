<!--   COMMENTS   


## Station d273HP1536 -- 35290303 -- DB5UAQWAK

### Monday Afternoon Coffee
+ Playlist: https://open.spotify.com/playlist/69z4MiLQlihRd9SA74JRQg?si=l5aBl8_wQvmAFY5VnnMo6w
+ https://open.spotify.com/track/4TAISq5tij3yPaeOs2Vle7?si=4108a81e363c4bc3
+ https://open.spotify.com/track/1ibRqifchaAfeNdQGpbRVW?si=c5b562c1110a40eb
+ https://open.spotify.com/track/5sra5UY6sD658OabHL3QtI?si=286b4e9a217f4b4f
+ https://open.spotify.com/track/5JTp5hsKJQIEUEe2M5QUvN?si=1e7a01b3ef7e4c6f

## Replay Memory: AGAIN
+ Configuring Replay Memory affects concept learning / potential.
+ Memory replay selection maybe part of prep for learning task.

+ Fruit Packing & Shipping Automation & Tracking w/ AI
 Getting ready for week:

+ 2.15.25 NYC

+ Issue 1:

### It's all about "Replay Memory"
+ What Goes In?
+ What Stays In?
+ How does it temper change & learning .... ..

```
class ReplayMemory:
    def __init__(self, max_length=None):
        self.max_length = max_length
        self.memory = deque(maxlen=max_length)

    def store(self, data):
        self.memory.append(data)

    def _sample(self, k):
        return random.sample(self.memory, k)

    def structured_sample(self, k):
        batch = self._sample(k)
        result = {}
        for i, part in enumerate(memory_parts):
            result[part] = np.array([row[i] for row in batch])

        return result

    def __len__(self):
        return len(self.memory)
```        
https://www.researchgate.net/publication/384119670_Predicting_Task_Activation_Maps_from_Resting-State_Functional_Connectivity_using_Deep_Learning
https://www.researchgate.net/publication/384631218_Realizable_Continuous-Space_Shields_for_Safe_Reinforcement_Learning
----------------------------------------------------------------------------------------------------------------------------------------------------------

**everestso/everestso** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

-->
