# load
load
https://fengyuanchen.github.io/datepicker/


https://jsfiddle.net/tz1nsg40/2/

package com.acss.hps.test;

import org.junit.Test;
import org.slf4j.Logger;
import org.slf4j.LoggerFactory;

public class TestJohnrey {
	
	private static final Logger logger = LoggerFactory.getLogger(TestJohnrey.class);
	
	public String varString;
	public char varChar;
	public int varInt;
	public boolean varBoolean;
	public double varDouble;
	public long varLong;
	public float varFloat;
	public byte varByte;
	public short varShort;
	
	@Test
	public void print() {
		logger.debug("String ==> " + varString); 	// null
		logger.debug("char ==> " + varChar);		// \u0000 == null == (little square)
		logger.debug("int ==> " + varInt);			// 0
		logger.debug("boolean ==> " + varBoolean);	// false
		logger.debug("double ==> " + varDouble);	// 0.0
		logger.debug("long ==> " + varLong);		// 0
		logger.debug("float ==> " + varFloat);		// 0.0
		logger.debug("byte ==> " + varByte);		// 0
		logger.debug("short ==> " + varShort);		// 0
	}

}



https://jsfiddle.net/tz1nsg40/7/





.msgError {
	background-image: url("http://demo.redmine.org/images/exclamation.png");
	background-position: 15px 13px;
	background-repeat: no-repeat;
	border: 1px solid #dd0000;
	background-color: #ffe3e3;
	padding: 10px;
	min-height: 26px;
	padding-left: 50px;
  padding-right:35px;
	margin-bottom: 10px;
	font-size: 12px;
  position: relative;
	}
	.msgError .error-text {
		line-height: 23px; 
		vertical-align: middle;
		color: #880000;
	}
	.msgError#unsupported-browser {
		display:none;
		position:fixed;
		width: 100%;
		z-index: 600;
		border-width: 0 0 1px 0;
	}
  
    .msgError .closeDialog,.msgWarning .closeDialog,.msgCheck .closeDialog {
    position: absolute;
    right: 12px;
    top: 50%;
    margin-top: -6px;
    width:12px;
    height:12px;
    /*background:url(https://2.bp.blogspot.com/-IuwrMRddJPA/Uj0EKnY22II/AAAAAAAAFhM/V6cKdl07Bxc/s1600/close.png);*/
   background:url(https://s15.postimg.cc/sap75ig4r/close1_opaque60.png);
    background-repeat: no-repeat;
	}
  
  .msgError .closeDialog:hover ,.msgWarning .closeDialog:hover ,.msgCheck .closeDialog:hover {
      background:url(https://s15.postimg.cc/6bisid4gb/close1_opaque30.png);
    }
  
 
 
 https://jsfiddle.net/tz1nsg40/9/
 
 https://jsfiddle.net/tz1nsg40/12/
 
 https://jsfiddle.net/tz1nsg40/16/


ttps://jsfiddle.net/tz1nsg40/20/

========================
https://s15.postimg.cc/e0fmuj7nf/close1_opaque50.png

https://s15.postimg.cc/4txc6upfv/close1.png

https://s15.postimg.cc/tafi1n34r/close1_opaque70.png

https://s15.postimg.cc/j1n0vi9uj/close2_opaque50.png

https://s15.postimg.cc/6n08vbniz/close2.png

https://s15.postimg.cc/sap75ig4r/close1_opaque60.png
