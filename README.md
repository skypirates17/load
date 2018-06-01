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
