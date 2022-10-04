# KataIdeas

The idea is to lead people into understanding what owns information that adapters return and develop patterns for handling this.


## Stage 1
A system consists of a sensor that returns temparature data, when that temparature reaches a certain threshold (80) it turns a warning light on, the buzzer needs to stay on even if the temperature returns below that threshold.


## Stage 2
When the temperature moves to below 50 the buzzer can turn off if somebody has issued a 'cycle the core' command. If it drops below 50 and cycle has not been issued then return an operator failure

## Stage 3
The owners of the system have noticed that some of the operators are not noticing the buzzer. They want the system to Use an alarm instead. They no longer need the buzzer.

## Stage 4
The owners of the system now want it so that some operators use a buzzer and some operators use a warning light.

## Stage 5
The buzzer is potentially a defective part and sometimes requires its buzziness to be recharged because they bought the organic environmentally safe version. When this happens it fails and issues a 'temporarily not available'  but will work again within 2 immediate attempts if retried (apparently there is some strange property of the system where time behaves strangley). The Owners want you to retry after 1 second.

## Stage 6
Apparently using just a light or a buzzer discriminates so now the owners want a smell to be released instead. Howevever smells are strange and if they are still temporarily unavailable adter 3 retries they should not be attempted again and  and the operator needs to be notified via the buzzer.

