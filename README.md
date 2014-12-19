ios-sdk
===========

IOS SDK for MoreGamers.com.

Installation
============

Add MoreGamers.m and MoreGamers.h to your project, then include MoreGamers.h in any source files that will use the MoreGamers class.

    #import "MoreGamers.h"

Initialize the MoreGamers class, replaceing XX with your Game ID.  The Initialize method may be called multiple times without any issue.

    [[MoreGamers sharedInstance] Initialize:XX]];

Display a Banner

    [[MoreGamers sharedInstance] Banner:CGRectMake(x, y, width, height)];

Hide the banner

    [[MoreGamers sharedInstance] Hide];
