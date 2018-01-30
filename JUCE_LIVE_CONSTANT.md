# Finetuning with JUCE_LIVE_CONSTANT
Use the JUCE_LIVE_CONSTANT to place and colorize components.
<br /><br />
<b>Simply surround a Color or Float for example with JUCE_LIVE_CONSTANT()</b><br />
JUCE_LIVE_CONSTANT(3.4f)<br />
JUCE_LIVE_CONSTANT(Colours::black)<br />
JUCE_LIVE_CONSTANT(Colour(0xff161616))<br />
sampleButton->setBounds (JUCE_LIVE_CONSTANT(0.20f), 0.025f, 0.04f, 0.09f);<br /><br />
<b>Make sure that there is only one JUCE_LIVE_CONSTANT per line!</b><br />

![Screenshot](https://raw.githubusercontent.com/Remberg/juce_workflow_tips/master/JUCE_LIVE_CONSTANT.gif)

