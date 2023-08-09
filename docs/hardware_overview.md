---
icon: material/cog
---

## Color Sensor - OPT4048

The OPT4048 measures the color properties of the light source that illuminates the device. It measures four channels with special spectral characteristics, which helps extract properties of the light source, color coordinates, lux level, and the correlated color temperature. This is useful for applications such as display brightness, color temperature adjustment, camera color temperature correction, object true color recognition & medical applications. For more information, refer to the [datasheet](assets/board_files/opt4048.pdf).

<div class="grid.cards.desc" markdown>

<table class="pdf" style="border-style:none;" markdown="1">
<tbody markdown="1">
<tr markdown="1">
<td align="center" width="35%" markdown="block">
[![SparkFun 6DoF - LSM6DSV16X (Qwiic)](assets/board_files/22638-SparkFun_Color_Sensor_OPT4048-BoardOutline.png){ width=90% }](assets/board_files/22638-SparkFun_Color_Sensor_OPT4048-BoardOutline.png)
</td>
<td align="center" width="35%" markdown="block">
[![SparkFun 6DoF Micro - LSM6DSV16X (Qwiic)](assets/board_files/22638-SparkFun_Color_Sensor_OPT4048-BoardOutline.png){ width=40% }](assets/board_files/22638-SparkFun_Color_Sensor_OPT4048-BoardOutline.png)
</td>
</tr>
</tbody>
</table>
</div class>




## Qwiic Connectors

VDD Range: 1.71V - 3.6V. 

###Power

Ideally, power to these boards will be provided by the Qwiic cables. However, should you wish to provide power separately, the 1" x 1" board has its pins broken out to PTH and you can wire up power via these. 

!!! warning
    <p>Make sure to pay attention to logic levels - supply voltage range should be between 1.71V - 3.6V. </p>


## GPIO


If you do not want to use the Qwiic connectors, I<sup>2</sup>C functionality has been broken out to PTH pins on the 1x1" board.

Interrupt pins


## LEDs

When appropriate power is provided to the board, the power LED lights up on the front of the board. 




## Jumpers

??? note "Never modified a jumper before?"
	Check out our <a href="https://learn.sparkfun.com/tutorials/664">Jumper Pads and PCB Traces tutorial</a> for a quick introduction!
	<p align="center">
		<a href="https://learn.sparkfun.com/tutorials/664">
		<img src="https://cdn.sparkfun.com/c/264-148/assets/learn_tutorials/6/6/4/PCB_TraceCutLumenati.jpg" alt="Tutorial's thumbnail"><br>
        How to Work with Jumper Pads and PCB Traces</a>
	</p>

### Address Selection 

The SparkFun Tristimulus Color Sensor - OPT4048DTSR (Qwiic) boards have a default I<sup>2</sup>C address of 0x44, but by manipulating the address jumper on the back of the board, you can select 0x45 or 0x46.



### LED Jumpers

If you are concerned about power consumption or you just don't like LEDs, cut the traces here to disconnect the Power LED from, well, power. 



### I2C

Like our other Qwiic boards, the SparkFun Tristimulus Color Sensor - OPT4048DTSR (Qwiic) boards come equipped with pull-up resistors on the clock and data pins. If you are daisy-chaining multiple Qwiic devices, you will want to cut this jumper; if multiple sensors are connected to the bus with the pull-up resistors enabled, the parallel equivalent resistance will create too strong of a pull-up for the bus to operate correctly. As a general rule of thumb, disable all but one pair of pull-up resistors if multiple devices are connected to the bus. To disable the pull up resistors, use an X-acto knife to cut the joint between the two jumper pads highlighted below.

## Board Dimensions

The SparkFun Tristimulus Color Sensor - OPT4048DTSR (Qwiic) follows the standard 1" x 1" convention of most of our Qwiic breakout boards. 

<figure markdown>
[![SparkFun Tristimulus Color Sensor - OPT4048DTSR (Qwiic) Board Outline](assets/board_files/22638-SparkFun_Color_Sensor_OPT4048-BoardOutline.png){ width=90% }](assets/board_files/22638-SparkFun_Color_Sensor_OPT4048-BoardOutline.png "Click to enlarge")
<figcaption markdown>SparkFun Tristimulus Color Sensor - OPT4048DTSR (Qwiic) Board Outline</figcaption>
</figure>

The SparkFun Mini Tristimulus Color Sensor - OPT4048DTSR (Qwiic) measures 1" x 0.5". 

<figure markdown>
[![SparkFun 6DoF - BMI270 (Qwiic) Board Outline](assets/board_files/22639-SparkFun_Color_Sensor_OPT4048-Mini-BoardOutline.png){ width=90% }](assets/board_files/22639-SparkFun_Color_Sensor_OPT4048-Mini-BoardOutline.png "Click to enlarge")
<figcaption markdown>SparkFun Mini Tristimulus Color Sensor - OPT4048DTSR (Qwiic) Board  Outline</figcaption>
</figure>














??? tip "Need more measurements?"
	For more information about the board's dimensions, users can download the [Eagle files](../assets/board_files/eagle_files.zip) for the board. These files can be opened in Eagle and additional measurements can be made with the dimensions tool.

	??? info ":octicons-download-16:{ .heart } Eagle - Free Download!"
		Eagle is a [CAD]("computer-aided design") program for electronics that is free to use for hobbyists and students. However, it does require an account registration to utilize the software.

		<center>
		[Download from<br>:autodesk-primary:{ .autodesk }](https://www.autodesk.com/products/eagle/free-download "Go to downloads page"){ .md-button .md-button--primary width="250px" }
		</center>
	
	??? info ":straight_ruler: Dimensions Tool"
		This video from Autodesk demonstrates how to utilize the dimensions tool in Eagle, to include additional measurements:

		<center>
		<div class="video">
		<iframe src="https://www.youtube.com/embed/dZLNd1FtNB8" title="EAGLE Dimension Tool" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
		</div>
		</center>