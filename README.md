
# libunn

Misc python scripts that i do not find anywhere to put them in

**Note: All of the scripts in this repository are written by me**



## Scripts

### Spinner
#### About:
Simple spinning bar that uses **threading** for running on the background
#### Usage:
```python
import libunn, time
libunn.spinner.start('Hello!')
time.sleep(2)
libunn.spinner.stop()
```
### Phrases

#### About:
Phrases is a simple module that manages a list (**phrases**), Upon start, Phrases contains 10 basic phrases, you can add more phrases, or delete them if you want, It is not for serious projects
#### Usage:
```python
import libunn
print(libunn.phrases.rand())
libunn.phrases.add("Hello, World!")
print(libunn.phrases.rand())
libunn.phrases.rm("Hello, World!")
```
## Installation

Install libunn with pip

```bash
  pip install libunn
```
    