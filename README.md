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



.msgWarning {
	background-image: url("http://demo.redmine.org/images/warning.png");
	background-position: 15px 13px;
	background-repeat: no-repeat;
	border: 1px solid rgb(246, 211, 87);
	background-color: rgb(252, 241, 202); 
	padding: 10px;
	min-height: 26px;
	padding-left: 50px;
  padding-right:35px;
	margin-bottom: 10px;
	font-size: 12px;
  position: relative;
	}
	.msgWarning .error-text {
		line-height: 23px; 
		vertical-align: middle;
		color: rgb(113,89,51);
	}
  
  .msgWarning .closeDialog {
    position: absolute;
    right: 15px;
    top: 50%;
    margin-top: -8px;
    width:15px;
    height:15px;
    background:url(http://www.app-branschinfo-kott.se/res/contact-close.png);
    background-repeat: no-repeat;
	}
 
