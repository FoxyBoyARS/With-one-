def difference_by(a, b, fn):
    b = set(map(fn, b))
    return [item for item in a if fn(item) not in b]

    from math import floor
difference_by([2.1, 1.2], [2.3, 3.4],floor) # [1.2]
difference_by([{ 'x': 2 }, { 'x': 1 }], [{ 'x': 1 }], lambda v : v['x']) # [ { x: 2 } ]
from functools import reduce


def spread(arg):
    ret = []
    for i in arg:
        if isinstance(i, list):
            ret.extend(i)
        else:
            ret.append(i)
    return ret


def lcm(*args):
    numbers = []
<Snippet>
  <Code Language="CSharp">
    <![CDATA[double root = Math.Sqrt($Number$);]]>
  </Code>
  <Declarations>
    <Literal>
      <ID>Number</ID>
      <ToolTip>Enter the number you want the square root of.</ToolTip>
      <Default>16</Default>
    </Literal>
  </Declarations>
</Snippet>
