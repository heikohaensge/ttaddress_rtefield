# Extend tt_address 4.0.0 - Extbase & Fluid Version of the pi-based tt_address

## Description

ttaddress_field is a sample extension to show how to extend the tt_address table.

## GitHub tt_address 4.x

https://github.com/BastianBalthasarBux/tt_address

## example output in tt_address fluid template

<!-- Additional RTE field of address -->
<f:if condition="{address.txTtaddressrtefieldRtecontent}">
	<f:then>
			<f:format.html>{address.txTtaddressrtefieldRtecontent}</f:format.html>
  </f:then>
</f:if>
