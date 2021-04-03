# US International Layout with code-friendly dead keys (Ctrl)

By default, Windows includes a layout called United States-International, which allows typing many non-ASCII characters. It is very useful for several Latin-script based languages.

The layout also designates several keys as "dead keys", particularly the apostrophe (') and double quotes ("). So to enter double quotes, you have to type " followed by space.

When writing code, this can be very annoying, since the apostrophe (') and double quotes (") are used frequenltly.

This repository contains a layout that is identical to United States-International but instead uses the Ctrl key in combination with the apostrophe ('), double quotes ("), circumflex (^), backtick (``) and tilde (~) as dead keys.

# How to build / install

The layout file can be opened with Microsoft's Keyboard Layout Creator (MKLC) tool, which Microsoft distributes for free. After opening the file in MKLC, choosing Project -> Build DLL and Setup Package will create an installer that can be used to add this layout to Windows.

**Remember** to log off and on again, in order for the changes to take effect.
