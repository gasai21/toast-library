<pre>

allprojects {
	repositories {
                ...
		<b>maven { url 'https://jitpack.io' }</b>
	}
}


dependencies {
        <b>implementation 'com.github.gasai21:first-library-:Tag'</b>
}
</pre>
