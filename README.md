# Alumni Sans Pinstripe

Alumni Pinstripe is a stand alone font from its base font, Alumni Sans (a variable font). Pinstripe is a super-thin weight and designed to be used as a display font. In situations that require large text, use this Pinstripe variation in combination with the Alumni Sans base design.

![Sample Image](documentation/image1.png)

## Building the Fonts

The font is built using fontmake and gftools post processing script. Tools are all python based, so it must be previously installed.

To install all the Python tools into a virtualenv, do the following:

From terminal:

```

cd your/local/project/directory

#once in the project folder create a virtual environment. 
This step has to be done just once, the first time:

python3 -m venv venv

#activate the virtual environment

source venv/bin/activate

#install the required dependencies

pip install -r requirements.txt

```

Then run the this command:

```
cd sources
gftools builder config.yml
```
