<!--   COMMENTS   


## Station d273HP -- 35290303 -- DB5UAQWAK

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
