# Zephyr_playground
Playing with Zephyr ecosystem


# Lessons learnt
- run zephyr-env.cmd to enable west workspace related commands.
- when one wants to use west manually without buttons from build tab: go to welcome tab insine vscode nrf connect extension -> manage toolchains -> open terminal profile.
- renesas flashing went out of the box with help of flashing with button from nrf connect
- stm flashing needed slight modification instead of "west flash -d c:\ncs\wkspc\example\blinky\build --domain blinky -i 602005882", correct command was "west flash -d c:\ncs\wkspc\example\blinky\build --domain blinky"
