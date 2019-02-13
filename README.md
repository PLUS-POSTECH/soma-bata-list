# soma-bata-list

This is a [Soma](https://github.com/PLUS-POSTECH/soma) repository for [BATA_24's pwn challenges list](https://pastebin.com/uyifxgPu).

Soma is a CTF problem management tool that allows you to easily setup and run problems in your local environment.

## How to Use

### Initial setup

1. Download and install [Soma](https://github.com/PLUS-POSTECH/soma)
2. `soma add https://github.com/PLUS-POSTECH/soma-bata-list.git`

### How to run a problem container

1. `soma build ${PROBLEM_NAME}` (in case of confliction, use `soma build soma-bata-list/${PROBLEM_NAME}`)
2. `soma run ${PROBLEM_NAME} ${PORT_NUMBER}`

## Problem List
Work in Progress

| Difficulty | Problem Name | Appeared in                                                  | License                                                      | Verified |
| ---------- | ------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | -------- |
| baby       | xkcd         | [DEF CON CTF Qualifier 2016](https://github.com/legitbs/quals-2016) | [CC BY-NC 4.0](https://github.com/legitbs/quals-2016/blob/master/LICENSE.md) | No       |
| baby       | r0pbaby      | [DEF CON CTF Qualifier 2015](https://github.com/legitbs/quals-2015) | [CC BY-NC 3.0](https://github.com/legitbs/quals-2015/blob/master/LICENSE.md) | No       |
| baby       | babyecho     | [DEF CON CTF Qualifier 2015](https://github.com/legitbs/quals-2015) | [CC BY-NC 3.0](https://github.com/legitbs/quals-2015/blob/master/LICENSE.md) | No       |

## Note About License

**We do not own the license of problem files.** We are redistributing them for an educational purpose, and we will do our best to properly credit original authors. Please create an issue if you are a problem author and want us to remove problem files from this repository.