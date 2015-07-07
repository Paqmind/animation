# Animation Notes

## IE
<table>
<tr><th>Version</th><th>setInterval</th><th>requestAnimationFrame</th></tr>
<tr><td>9-</td><td>not affected</td><td>not supported</td></tr>
<tr><td>10+</td><td>not affected</td><td>paused</td></tr>
</table>

## Chrome
<table>
<tr><th>Version</th><th>setInterval</th><th>requestAnimationFrame</th></tr>
<tr><td>9-</td><td>not affected</td><td>not supported</td></tr>
<tr><td>10</td><td>not affected</td><td>paused</td></tr>
<tr><td>11+</td><td>>=1000ms</td><td>paused</td></tr>
</table>

## Firefox
<table>
<tr><th>Version</th><th>setInterval</th><th>requestAnimationFrame</th></tr>
<tr><td>3-</td><td>not affected</td><td>not supported</td></tr>
<tr><td>4</td><td>not affected</td><td>1s</td></tr>
<tr><td>5+</td><td>>=1000ms</td><td>(2^n)s </td></tr>    
</table>
Where n is number of frames since inactivity

## Safari
<table>
<tr><th>Version</th><th>setInterval</th><th>requestAnimationFrame</th></tr>
<tr><td>5-</td><td>not affected</td><td>not supported</td></tr>
<tr><td>6</td><td>not affected</td><td>paused</td></tr>
<tr><td>7+</td><td>>=1000ms</td><td>paused</td></tr>    
</table>  
  
## Operat  
<table>  
<tr><th>Version</th><th>setInterval</th><th>requestAnimationFrame</th></tr>
<tr><td>12-</td><td>not affected</td><td>not supported</td></tr>
<tr><td>15+</td><td>>=1000ms</td><td>paused</td></tr>
</table>
