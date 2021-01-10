# Abstract

Medium voltage overhead power lines run for hundreds of miles to supply power to cities. These great distances make it expensive to manually inspect the lines for damage that doesn't immediately lead to a power outage, such as a tree branch hitting the line or a flaw in the insulator. These modes of damage lead to a phenomenon known as partial discharge — an electrical discharge which does not bridge the electrodes between an insulation system completely. Partial discharges slowly damage the power line, so left unrepaired they will eventually lead to a power outage or start a fire.

My aim is to detect partial discharge patterns in signals acquired from these power lines. By developing a solution to detect partial discharge there will be reduced maintenance costs, and will prevent power outages.

The main task here is to evaluate 'Matthews Correlation Coefficient' between the predicted and the observed response.

The MCC is given by the following formula -

                         MCC =         (TP∗TN)−(FP∗FN)
                               -----------------------------
                               √(TP+FP)(TP+FN)(TN+FP)(TN+FN)
                               
                   
