# Lab 3: Networks over Time

## Create Network from Data

Use the notebook provided. It will guide you through the process of creating a network from the data you collected in the previous labs.

## Import into Gephi

Open the network with Gephi. Make sure the time representation is set to timestamps. Use sum as the merge strategy. Is this network directed or undirected? Why?

## Prepare for Animation

Switch to the Data Laboratory and inspect the edges. Copy the time column to the timestamp column and enable the timeline. Play around with the timeline and see what happens.

## Create a Layout with Force Atlas 2

Switch back to Overview. Try tuning the different layout parameters. The most important will be scaling, and see what happens. If you click on the name of a parameter, Gephi will provide an explanation of what it does.

Don't forget to prevent overlap at the end.

You can also try the other layouts.

## Create a Ranking

Use the (undirected?) page rank statistic to create a ranking. Use the ranking to adjust the size of the nodes. Try a spline.

You might want to adjust the layout again because of overlap.

## Show the hashtags

Use the 'engineers board' icon to use the Ids as labels.

Use the 'eject' button on the lower right to show the respective display options. Activate node labels, make the size node sized. Adjust the size with the Node slider.

## Create a Partition

Create a partition using the modularity statistic. Colour the nodes by the partition. (You might want to use the Palette function to create more colours.) Repeat this several times, and see what happens.

## Create an Animation

Create an appropriate time window, move it and use the play button. Adjust the settings to your liking. You can also choose the date format.

Now activate the Force Atlas 2 layout and play the animation. What do you see? Can you find good parameters for the whole animation? (Hint: Try 'Dissuade Hubs'.)

Which dynamics can you see over time?

## Now repeat the same with the other network!