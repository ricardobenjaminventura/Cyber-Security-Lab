# Cyber-Security-Lab
Since graduating I built this multinode simulated enterprise network for penetration and security testing. It has redundant trunk links including two PfSense firewalls in the DMZ.  Kali Linux was used for testing on the metasploitable and DC-1 vulnerable machines that simulate users. I included another remote network that utilizes CloudStack that emulates any IAAS requirments for testing cloud environments. This is an ongoing project as I hone what I've learned in Cyber Security and build on my previous Network Engineering knowledge. [My High Level Diagram.drawio](https://github.com/user-attachments/files/28226800/My.High.Level.Diagram.drawio)
<mxfile host="Electron">
  <diagram name="Page-1" id="z-3YO7cawNHSfMap9C_Z">
    <mxGraphModel dx="2998" dy="921" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="850" pageHeight="1100" math="0" shadow="0">
      <root>
        <mxCell id="0" />
        <mxCell id="1" parent="0" />
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-174" parent="1" style="whiteSpace=wrap;html=1;" value="" vertex="1">
          <mxGeometry height="730" width="1140" x="230" y="330" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-187" parent="1" style="whiteSpace=wrap;html=1;" value="" vertex="1">
          <mxGeometry height="480" width="110" x="1040" y="472.5" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-188" parent="1" style="whiteSpace=wrap;html=1;" value="" vertex="1">
          <mxGeometry height="480" width="210" x="1150" y="472.5" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-185" parent="1" style="whiteSpace=wrap;html=1;" value="" vertex="1">
          <mxGeometry height="480" width="90" x="945" y="472.5" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-182" parent="1" style="whiteSpace=wrap;html=1;" value="" vertex="1">
          <mxGeometry height="490" width="220" x="720" y="470" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-181" parent="1" style="whiteSpace=wrap;html=1;" value="" vertex="1">
          <mxGeometry height="480" width="150" x="565" y="472.5" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-172" parent="1" style="whiteSpace=wrap;html=1;" value="" vertex="1">
          <mxGeometry height="560" width="240" x="-800" y="420" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-163" parent="1" style="whiteSpace=wrap;html=1;" value="" vertex="1">
          <mxGeometry height="560" width="230" x="-540" y="420" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-176" edge="1" parent="1" source="7jQLxiFZPrQ-dQYmUEen-162" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0;entryY=0.5;entryDx=0;entryDy=0;endArrow=none;endFill=0;" target="7jQLxiFZPrQ-dQYmUEen-174">
          <mxGeometry relative="1" as="geometry">
            <Array as="points">
              <mxPoint x="230" y="700" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-162" parent="1" style="whiteSpace=wrap;html=1;" value="" vertex="1">
          <mxGeometry height="560" width="230" x="-60" y="420" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-161" parent="1" style="whiteSpace=wrap;html=1;" value="" vertex="1">
          <mxGeometry height="560" width="180" x="-270" y="420" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-1" parent="1" style="sketch=0;points=[[0.015,0.015,0],[0.985,0.015,0],[0.985,0.985,0],[0.015,0.985,0],[0.25,0,0],[0.5,0,0],[0.75,0,0],[1,0.25,0],[1,0.5,0],[1,0.75,0],[0.75,1,0],[0.5,1,0],[0.25,1,0],[0,0.75,0],[0,0.5,0],[0,0.25,0]];verticalLabelPosition=bottom;html=1;verticalAlign=top;aspect=fixed;align=center;pointerEvents=1;shape=mxgraph.cisco19.rect;prIcon=firewall;fillColor=#FAFAFA;strokeColor=#005073;" value="" vertex="1">
          <mxGeometry height="50" width="64" x="780" y="592.5" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-2" parent="1" style="sketch=0;points=[[0.015,0.015,0],[0.985,0.015,0],[0.985,0.985,0],[0.015,0.985,0],[0.25,0,0],[0.5,0,0],[0.75,0,0],[1,0.25,0],[1,0.5,0],[1,0.75,0],[0.75,1,0],[0.5,1,0],[0.25,1,0],[0,0.75,0],[0,0.5,0],[0,0.25,0]];verticalLabelPosition=bottom;html=1;verticalAlign=top;aspect=fixed;align=center;pointerEvents=1;shape=mxgraph.cisco19.rect;prIcon=firewall;fillColor=#FAFAFA;strokeColor=#005073;" value="" vertex="1">
          <mxGeometry height="50" width="64" x="780" y="772.5" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-3" parent="1" style="sketch=0;pointerEvents=1;shadow=0;dashed=0;html=1;strokeColor=none;fillColor=#505050;labelPosition=center;verticalLabelPosition=bottom;outlineConnect=0;verticalAlign=top;align=center;shape=mxgraph.office.clouds.cloud;" value="" vertex="1">
          <mxGeometry height="55" width="94" x="420" y="770" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-4" parent="1" style="sketch=0;pointerEvents=1;shadow=0;dashed=0;html=1;strokeColor=none;fillColor=#505050;labelPosition=center;verticalLabelPosition=bottom;outlineConnect=0;verticalAlign=top;align=center;shape=mxgraph.office.clouds.cloud;" value="" vertex="1">
          <mxGeometry height="55" width="90" x="420" y="590" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-7" parent="1" style="sketch=0;points=[[0.015,0.015,0],[0.985,0.015,0],[0.985,0.985,0],[0.015,0.985,0],[0.25,0,0],[0.5,0,0],[0.75,0,0],[1,0.25,0],[1,0.5,0],[1,0.75,0],[0.75,1,0],[0.5,1,0],[0.25,1,0],[0,0.75,0],[0,0.5,0],[0,0.25,0]];verticalLabelPosition=bottom;html=1;verticalAlign=top;aspect=fixed;align=center;pointerEvents=1;shape=mxgraph.cisco19.rect;prIcon=l3_switch;fillColor=#FAFAFA;strokeColor=#005073;" value="" vertex="1">
          <mxGeometry height="50" width="50" x="965" y="772.5" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-8" parent="1" style="sketch=0;points=[[0.015,0.015,0],[0.985,0.015,0],[0.985,0.985,0],[0.015,0.985,0],[0.25,0,0],[0.5,0,0],[0.75,0,0],[1,0.25,0],[1,0.5,0],[1,0.75,0],[0.75,1,0],[0.5,1,0],[0.25,1,0],[0,0.75,0],[0,0.5,0],[0,0.25,0]];verticalLabelPosition=bottom;html=1;verticalAlign=top;aspect=fixed;align=center;pointerEvents=1;shape=mxgraph.cisco19.rect;prIcon=l3_switch;fillColor=#FAFAFA;strokeColor=#005073;" value="" vertex="1">
          <mxGeometry height="50" width="50" x="965" y="592.5" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-9" parent="1" style="sketch=0;points=[[0.015,0.015,0],[0.985,0.015,0],[0.985,0.985,0],[0.015,0.985,0],[0.25,0,0],[0.5,0,0],[0.75,0,0],[1,0.25,0],[1,0.5,0],[1,0.75,0],[0.75,1,0],[0.5,1,0],[0.25,1,0],[0,0.75,0],[0,0.5,0],[0,0.25,0]];verticalLabelPosition=bottom;html=1;verticalAlign=top;aspect=fixed;align=center;pointerEvents=1;shape=mxgraph.cisco19.rect;prIcon=l2_switch;fillColor=#FAFAFA;strokeColor=#005073;" value="" vertex="1">
          <mxGeometry height="50" width="50" x="660" y="592.5" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-10" parent="1" style="sketch=0;points=[[0.015,0.015,0],[0.985,0.015,0],[0.985,0.985,0],[0.015,0.985,0],[0.25,0,0],[0.5,0,0],[0.75,0,0],[1,0.25,0],[1,0.5,0],[1,0.75,0],[0.75,1,0],[0.5,1,0],[0.25,1,0],[0,0.75,0],[0,0.5,0],[0,0.25,0]];verticalLabelPosition=bottom;html=1;verticalAlign=top;aspect=fixed;align=center;pointerEvents=1;shape=mxgraph.cisco19.rect;prIcon=l2_switch;fillColor=#FAFAFA;strokeColor=#005073;" value="" vertex="1">
          <mxGeometry height="50" width="50" x="660" y="772.5" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-30" edge="1" parent="1" source="7jQLxiFZPrQ-dQYmUEen-11" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;strokeWidth=1;endArrow=none;endFill=0;" target="7jQLxiFZPrQ-dQYmUEen-3">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-11" parent="1" style="sketch=0;points=[[0.5,0,0],[1,0.5,0],[0.5,1,0],[0,0.5,0],[0.145,0.145,0],[0.8555,0.145,0],[0.855,0.8555,0],[0.145,0.855,0]];verticalLabelPosition=bottom;html=1;verticalAlign=top;aspect=fixed;align=center;pointerEvents=1;shape=mxgraph.cisco19.rect;prIcon=router;fillColor=#FAFAFA;strokeColor=#005073;" value="" vertex="1">
          <mxGeometry height="50" width="50" x="570" y="772.5" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-31" edge="1" parent="1" source="7jQLxiFZPrQ-dQYmUEen-12" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;endArrow=none;endFill=0;" target="7jQLxiFZPrQ-dQYmUEen-4">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-12" parent="1" style="sketch=0;points=[[0.5,0,0],[1,0.5,0],[0.5,1,0],[0,0.5,0],[0.145,0.145,0],[0.8555,0.145,0],[0.855,0.8555,0],[0.145,0.855,0]];verticalLabelPosition=bottom;html=1;verticalAlign=top;aspect=fixed;align=center;pointerEvents=1;shape=mxgraph.cisco19.rect;prIcon=router;fillColor=#FAFAFA;strokeColor=#005073;" value="" vertex="1">
          <mxGeometry height="50" width="50" x="570" y="592.5" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-17" parent="1" style="sketch=0;points=[[0.015,0.015,0],[0.985,0.015,0],[0.985,0.985,0],[0.015,0.985,0],[0.25,0,0],[0.5,0,0],[0.75,0,0],[1,0.25,0],[1,0.5,0],[1,0.75,0],[0.75,1,0],[0.5,1,0],[0.25,1,0],[0,0.75,0],[0,0.5,0],[0,0.25,0]];verticalLabelPosition=bottom;html=1;verticalAlign=top;aspect=fixed;align=center;pointerEvents=1;shape=mxgraph.cisco19.rect;prIcon=l2_switch;fillColor=#FAFAFA;strokeColor=#005073;" value="" vertex="1">
          <mxGeometry height="50" width="50" x="1070" y="772.5" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-18" parent="1" style="sketch=0;points=[[0.015,0.015,0],[0.985,0.015,0],[0.985,0.985,0],[0.015,0.985,0],[0.25,0,0],[0.5,0,0],[0.75,0,0],[1,0.25,0],[1,0.5,0],[1,0.75,0],[0.75,1,0],[0.5,1,0],[0.25,1,0],[0,0.75,0],[0,0.5,0],[0,0.25,0]];verticalLabelPosition=bottom;html=1;verticalAlign=top;aspect=fixed;align=center;pointerEvents=1;shape=mxgraph.cisco19.rect;prIcon=l2_switch;fillColor=#FAFAFA;strokeColor=#005073;" value="" vertex="1">
          <mxGeometry height="50" width="50" x="1070" y="592.5" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-34" edge="1" parent="1" source="7jQLxiFZPrQ-dQYmUEen-26" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;endArrow=none;endFill=0;dashed=1;entryX=0.5;entryY=0;entryDx=0;entryDy=0;entryPerimeter=0;" target="7jQLxiFZPrQ-dQYmUEen-27">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="755" y="860" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-26" parent="1" style="sketch=0;points=[[0.015,0.015,0],[0.985,0.015,0],[0.985,0.985,0],[0.015,0.985,0],[0.25,0,0],[0.5,0,0],[0.75,0,0],[1,0.25,0],[1,0.5,0],[1,0.75,0],[0.75,1,0],[0.5,1,0],[0.25,1,0],[0,0.75,0],[0,0.5,0],[0,0.25,0]];verticalLabelPosition=bottom;html=1;verticalAlign=top;aspect=fixed;align=center;pointerEvents=1;shape=mxgraph.cisco19.rect;prIcon=l2_switch;fillColor=#FAFAFA;strokeColor=#005073;" value="" vertex="1">
          <mxGeometry height="50" width="50" x="730" y="500" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-27" parent="1" style="sketch=0;points=[[0.015,0.015,0],[0.985,0.015,0],[0.985,0.985,0],[0.015,0.985,0],[0.25,0,0],[0.5,0,0],[0.75,0,0],[1,0.25,0],[1,0.5,0],[1,0.75,0],[0.75,1,0],[0.5,1,0],[0.25,1,0],[0,0.75,0],[0,0.5,0],[0,0.25,0]];verticalLabelPosition=bottom;html=1;verticalAlign=top;aspect=fixed;align=center;pointerEvents=1;shape=mxgraph.cisco19.rect;prIcon=l2_switch;fillColor=#FAFAFA;strokeColor=#005073;" value="" vertex="1">
          <mxGeometry height="50" width="50" x="730" y="862.5" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-28" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="DMZ" vertex="1">
          <mxGeometry height="30" width="60" x="725" y="470" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-29" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="DMZ" vertex="1">
          <mxGeometry height="30" width="60" x="725" y="922.5" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-32" edge="1" parent="1" source="7jQLxiFZPrQ-dQYmUEen-10" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=1;entryY=0.5;entryDx=0;entryDy=0;entryPerimeter=0;endArrow=none;endFill=0;" target="7jQLxiFZPrQ-dQYmUEen-11">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-33" edge="1" parent="1" source="7jQLxiFZPrQ-dQYmUEen-9" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=1;entryY=0.5;entryDx=0;entryDy=0;entryPerimeter=0;endArrow=none;endFill=0;" target="7jQLxiFZPrQ-dQYmUEen-12">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-36" edge="1" parent="1" source="7jQLxiFZPrQ-dQYmUEen-2" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0.5;entryY=1;entryDx=0;entryDy=0;entryPerimeter=0;endArrow=none;endFill=0;" target="7jQLxiFZPrQ-dQYmUEen-1">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-37" edge="1" parent="1" source="7jQLxiFZPrQ-dQYmUEen-1" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=1;entryY=0.5;entryDx=0;entryDy=0;entryPerimeter=0;endArrow=none;endFill=0;" target="7jQLxiFZPrQ-dQYmUEen-9">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-38" edge="1" parent="1" source="7jQLxiFZPrQ-dQYmUEen-2" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=1;entryY=0.5;entryDx=0;entryDy=0;entryPerimeter=0;endArrow=none;endFill=0;" target="7jQLxiFZPrQ-dQYmUEen-10">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-39" parent="1" style="sketch=0;points=[[0.015,0.015,0],[0.985,0.015,0],[0.985,0.985,0],[0.015,0.985,0],[0.25,0,0],[0.5,0,0],[0.75,0,0],[1,0.25,0],[1,0.5,0],[1,0.75,0],[0.75,1,0],[0.5,1,0],[0.25,1,0],[0,0.75,0],[0,0.5,0],[0,0.25,0]];verticalLabelPosition=bottom;html=1;verticalAlign=top;aspect=fixed;align=center;pointerEvents=1;shape=mxgraph.cisco19.rect;prIcon=l2_switch;fillColor=#FAFAFA;strokeColor=#005073;" value="" vertex="1">
          <mxGeometry height="50" width="50" x="844" y="680" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-45" edge="1" parent="1" source="7jQLxiFZPrQ-dQYmUEen-39" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=1;entryY=0.75;entryDx=0;entryDy=0;entryPerimeter=0;endArrow=none;endFill=0;" target="7jQLxiFZPrQ-dQYmUEen-1">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-46" edge="1" parent="1" source="7jQLxiFZPrQ-dQYmUEen-39" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=1;entryY=0.25;entryDx=0;entryDy=0;entryPerimeter=0;endArrow=none;endFill=0;" target="7jQLxiFZPrQ-dQYmUEen-2">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-47" edge="1" parent="1" source="7jQLxiFZPrQ-dQYmUEen-8" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=1;entryY=0.5;entryDx=0;entryDy=0;entryPerimeter=0;endArrow=none;endFill=0;" target="7jQLxiFZPrQ-dQYmUEen-1">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-50" edge="1" parent="1" source="7jQLxiFZPrQ-dQYmUEen-7" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=1;entryY=0.5;entryDx=0;entryDy=0;entryPerimeter=0;endArrow=none;endFill=0;" target="7jQLxiFZPrQ-dQYmUEen-2">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-51" edge="1" parent="1" source="7jQLxiFZPrQ-dQYmUEen-18" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=1;entryY=0.5;entryDx=0;entryDy=0;entryPerimeter=0;endArrow=none;endFill=0;" target="7jQLxiFZPrQ-dQYmUEen-8">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-52" edge="1" parent="1" source="7jQLxiFZPrQ-dQYmUEen-17" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=1;entryY=0.5;entryDx=0;entryDy=0;entryPerimeter=0;endArrow=none;endFill=0;" target="7jQLxiFZPrQ-dQYmUEen-7">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-57" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="WinServer DHCP" vertex="1">
          <mxGeometry height="30" width="60" x="1270" y="555" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-58" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="DC-1" vertex="1">
          <mxGeometry height="30" width="60" x="1270" y="827.5" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-61" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="Metasploitable" vertex="1">
          <mxGeometry height="30" width="60" x="1280" y="650" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-62" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="Metasploitable" vertex="1">
          <mxGeometry height="30" width="60" x="1280" y="735" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-63" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="Access Switch" vertex="1">
          <mxGeometry height="30" width="60" x="1065" y="560" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-64" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="Access Switch" vertex="1">
          <mxGeometry height="30" width="60" x="1065" y="822.5" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-65" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="Core Switch" vertex="1">
          <mxGeometry height="30" width="60" x="960" y="560" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-66" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="Core Switch" vertex="1">
          <mxGeometry height="30" width="60" x="960" y="822.5" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-67" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="PfSense Firewall" vertex="1">
          <mxGeometry height="30" width="60" x="782" y="560" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-68" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="PfSense Firewall" vertex="1">
          <mxGeometry height="30" width="60" x="782" y="822.5" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-69" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="FW Management&amp;nbsp;" vertex="1">
          <mxGeometry height="30" width="60" x="870" y="922.5" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-71" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="Edge Router" vertex="1">
          <mxGeometry height="30" width="60" x="565" y="562.5" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-72" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="Edge Router" vertex="1">
          <mxGeometry height="30" width="60" x="565" y="827.5" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-73" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="Ext Switch" vertex="1">
          <mxGeometry height="30" width="60" x="655" y="562.5" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-74" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="Ext Switch" vertex="1">
          <mxGeometry height="30" width="60" x="655" y="822.5" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-75" edge="1" parent="1" source="7jQLxiFZPrQ-dQYmUEen-26" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0.015;entryY=0.015;entryDx=0;entryDy=0;entryPerimeter=0;endArrow=none;endFill=0;" target="7jQLxiFZPrQ-dQYmUEen-1">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-76" edge="1" parent="1" source="7jQLxiFZPrQ-dQYmUEen-27" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0.015;entryY=0.985;entryDx=0;entryDy=0;entryPerimeter=0;endArrow=none;endFill=0;" target="7jQLxiFZPrQ-dQYmUEen-2">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-78" edge="1" parent="1" source="7jQLxiFZPrQ-dQYmUEen-8" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0.5;entryY=0;entryDx=0;entryDy=0;entryPerimeter=0;endArrow=none;endFill=0;" target="7jQLxiFZPrQ-dQYmUEen-7">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-79" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="Management Switch" vertex="1">
          <mxGeometry height="30" width="60" x="885" y="660" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-85" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="Tailscale&lt;div&gt;VPN&lt;/div&gt;" vertex="1">
          <mxGeometry height="30" width="60" x="260" y="565" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-86" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="Wazuh Endpoint Management" vertex="1">
          <mxGeometry height="30" width="60" x="260" y="647.5" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-87" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="Zabbix Network Management" vertex="1">
          <mxGeometry height="30" width="60" x="260" y="817.5" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-88" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="EVE-NG" vertex="1">
          <mxGeometry height="30" width="60" x="260" y="735" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-92" edge="1" parent="1" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0.5;entryY=1;entryDx=0;entryDy=0;entryPerimeter=0;endArrow=none;endFill=0;">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="355" y="812.5" as="sourcePoint" />
            <mxPoint x="355" y="765" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-93" edge="1" parent="1" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0.5;entryY=0;entryDx=0;entryDy=0;entryPerimeter=0;endArrow=none;endFill=0;">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="355" y="682.5" as="sourcePoint" />
            <mxPoint x="355" y="725" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-95" parent="1" style="sketch=0;points=[[0.5,0,0],[1,0.5,0],[0.5,1,0],[0,0.5,0],[0.145,0.145,0],[0.8555,0.145,0],[0.855,0.8555,0],[0.145,0.855,0]];verticalLabelPosition=bottom;html=1;verticalAlign=top;aspect=fixed;align=center;pointerEvents=1;shape=mxgraph.cisco19.rect;prIcon=router_with_firewall;fillColor=#FAFAFA;strokeColor=#005073;" value="" vertex="1">
          <mxGeometry height="50" width="50" x="-40" y="682.5" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-96" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="Ubiquiti Dream Machine SE" vertex="1">
          <mxGeometry height="30" width="60" x="-45" y="750" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-97" parent="1" style="sketch=0;pointerEvents=1;shadow=0;dashed=0;html=1;strokeColor=none;fillColor=#505050;labelPosition=center;verticalLabelPosition=bottom;outlineConnect=0;verticalAlign=top;align=center;shape=mxgraph.office.clouds.cloud;" value="" vertex="1">
          <mxGeometry height="55" width="94" x="-230" y="682.5" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-139" edge="1" parent="1" source="7jQLxiFZPrQ-dQYmUEen-98" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;endArrow=none;endFill=0;" target="7jQLxiFZPrQ-dQYmUEen-97">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-98" parent="1" style="sketch=0;points=[[0.5,0,0],[1,0.5,0],[0.5,1,0],[0,0.5,0],[0.145,0.145,0],[0.8555,0.145,0],[0.855,0.8555,0],[0.145,0.855,0]];verticalLabelPosition=bottom;html=1;verticalAlign=top;aspect=fixed;align=center;pointerEvents=1;shape=mxgraph.cisco19.rect;prIcon=router_with_firewall;fillColor=#FAFAFA;strokeColor=#005073;" value="" vertex="1">
          <mxGeometry height="50" width="50" x="-380" y="685" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-99" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="Ubiquiti Dream Machine SE" vertex="1">
          <mxGeometry height="40" width="60" x="-385" y="745" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-106" edge="1" parent="1" source="7jQLxiFZPrQ-dQYmUEen-100" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0;entryY=0.25;entryDx=0;entryDy=0;endArrow=none;endFill=0;dashed=1;dashPattern=1 4;" target="7jQLxiFZPrQ-dQYmUEen-85">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-100" parent="1" style="outlineConnect=0;dashed=0;verticalLabelPosition=bottom;verticalAlign=top;align=center;html=1;shape=mxgraph.aws3.vpn_connection;fillColor=#F58534;gradientColor=none;" value="" vertex="1">
          <mxGeometry height="48" width="58.5" x="-212.25" y="549.5" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-102" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="Tailscale&lt;div&gt;VPN&lt;/div&gt;" vertex="1">
          <mxGeometry height="30" width="60" x="-690" y="562.5" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-109" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="DC-1" vertex="1">
          <mxGeometry height="30" width="60" x="-785" y="667.5" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-110" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="Metasploitable" vertex="1">
          <mxGeometry height="30" width="60" x="-785" y="835" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-113" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="Cloudstack IAAS" vertex="1">
          <mxGeometry height="30" width="60" x="-630" y="787.5" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-115" parent="1" style="verticalLabelPosition=bottom;html=1;verticalAlign=top;align=center;strokeColor=none;fillColor=#00BEF2;shape=mxgraph.azure.virtual_machine;" value="" vertex="1">
          <mxGeometry height="40" width="50" x="1220" y="549.5" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-116" parent="1" style="image;html=1;image=img/lib/clip_art/computers/Server_128x128.png" value="" vertex="1">
          <mxGeometry height="80" width="80" x="70" y="667.5" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-117" parent="1" style="image;html=1;image=img/lib/clip_art/computers/Server_128x128.png" value="" vertex="1">
          <mxGeometry height="80" width="80" x="-520" y="670" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-119" parent="1" style="verticalLabelPosition=bottom;html=1;verticalAlign=top;align=center;strokeColor=none;fillColor=#00BEF2;shape=mxgraph.azure.virtual_machine;" value="" vertex="1">
          <mxGeometry height="40" width="50" x="1220" y="735" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-120" parent="1" style="verticalLabelPosition=bottom;html=1;verticalAlign=top;align=center;strokeColor=none;fillColor=#00BEF2;shape=mxgraph.azure.virtual_machine;" value="" vertex="1">
          <mxGeometry height="40" width="50" x="1220" y="647.5" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-121" parent="1" style="verticalLabelPosition=bottom;html=1;verticalAlign=top;align=center;strokeColor=none;fillColor=#00BEF2;shape=mxgraph.azure.virtual_machine;" value="" vertex="1">
          <mxGeometry height="40" width="50" x="330" y="560" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-122" parent="1" style="verticalLabelPosition=bottom;html=1;verticalAlign=top;align=center;strokeColor=none;fillColor=#00BEF2;shape=mxgraph.azure.virtual_machine;" value="" vertex="1">
          <mxGeometry height="40" width="50" x="-625" y="555" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-171" edge="1" parent="1" source="7jQLxiFZPrQ-dQYmUEen-123" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0;entryY=0.5;entryDx=0;entryDy=0;endArrow=none;endFill=0;" target="7jQLxiFZPrQ-dQYmUEen-163">
          <mxGeometry relative="1" as="geometry">
            <Array as="points">
              <mxPoint x="-600" y="700" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-123" parent="1" style="verticalLabelPosition=bottom;html=1;verticalAlign=top;align=center;strokeColor=none;fillColor=#00BEF2;shape=mxgraph.azure.virtual_machine;" value="" vertex="1">
          <mxGeometry height="40" width="50" x="-625" y="747.5" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-124" parent="1" style="verticalLabelPosition=bottom;html=1;verticalAlign=top;align=center;strokeColor=none;fillColor=#00BEF2;shape=mxgraph.azure.virtual_machine;" value="" vertex="1">
          <mxGeometry height="40" width="50" x="-780" y="795" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-125" parent="1" style="verticalLabelPosition=bottom;html=1;verticalAlign=top;align=center;strokeColor=none;fillColor=#00BEF2;shape=mxgraph.azure.virtual_machine;" value="" vertex="1">
          <mxGeometry height="40" width="50" x="-780" y="700" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-128" parent="1" style="verticalLabelPosition=bottom;html=1;verticalAlign=top;align=center;strokeColor=none;fillColor=#00BEF2;shape=mxgraph.azure.virtual_machine;" value="" vertex="1">
          <mxGeometry height="40" width="50" x="330" y="645" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-129" parent="1" style="verticalLabelPosition=bottom;html=1;verticalAlign=top;align=center;strokeColor=none;fillColor=#00BEF2;shape=mxgraph.azure.virtual_machine;" value="" vertex="1">
          <mxGeometry height="40" width="50" x="330" y="730" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-130" parent="1" style="verticalLabelPosition=bottom;html=1;verticalAlign=top;align=center;strokeColor=none;fillColor=#00BEF2;shape=mxgraph.azure.virtual_machine;" value="" vertex="1">
          <mxGeometry height="40" width="50" x="330" y="812.5" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-132" edge="1" parent="1" source="7jQLxiFZPrQ-dQYmUEen-4" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=1;entryY=0.5;entryDx=0;entryDy=0;entryPerimeter=0;endArrow=none;endFill=0;" target="7jQLxiFZPrQ-dQYmUEen-129">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-134" edge="1" parent="1" source="7jQLxiFZPrQ-dQYmUEen-3" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=1;entryY=0.5;entryDx=0;entryDy=0;entryPerimeter=0;endArrow=none;endFill=0;" target="7jQLxiFZPrQ-dQYmUEen-129">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-137" edge="1" parent="1" source="7jQLxiFZPrQ-dQYmUEen-117" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0;entryY=0.5;entryDx=0;entryDy=0;entryPerimeter=0;endArrow=none;endFill=0;" target="7jQLxiFZPrQ-dQYmUEen-98">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-138" edge="1" parent="1" source="7jQLxiFZPrQ-dQYmUEen-116" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=1;entryY=0.5;entryDx=0;entryDy=0;entryPerimeter=0;endArrow=none;endFill=0;" target="7jQLxiFZPrQ-dQYmUEen-95">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-141" edge="1" parent="1" source="7jQLxiFZPrQ-dQYmUEen-95" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;endArrow=none;endFill=0;">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="-140" y="708" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-146" edge="1" parent="1" source="7jQLxiFZPrQ-dQYmUEen-123" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=1;entryY=0.5;entryDx=0;entryDy=0;entryPerimeter=0;endArrow=none;endFill=0;" target="7jQLxiFZPrQ-dQYmUEen-125">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-147" edge="1" parent="1" source="7jQLxiFZPrQ-dQYmUEen-123" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=1;entryY=0.5;entryDx=0;entryDy=0;entryPerimeter=0;endArrow=none;endFill=0;" target="7jQLxiFZPrQ-dQYmUEen-124">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-150" edge="1" parent="1" source="7jQLxiFZPrQ-dQYmUEen-100" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=1;entryY=0.5;entryDx=0;entryDy=0;entryPerimeter=0;endArrow=none;endFill=0;dashed=1;dashPattern=1 4;" target="7jQLxiFZPrQ-dQYmUEen-122">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-152" parent="1" style="verticalLabelPosition=bottom;html=1;verticalAlign=top;align=center;strokeColor=none;fillColor=#00BEF2;shape=mxgraph.azure.virtual_machine;" value="" vertex="1">
          <mxGeometry height="40" width="50" x="1220" y="822.5" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-153" edge="1" parent="1" source="7jQLxiFZPrQ-dQYmUEen-18" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0;entryY=0.5;entryDx=0;entryDy=0;entryPerimeter=0;endArrow=none;endFill=0;" target="7jQLxiFZPrQ-dQYmUEen-115">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-154" edge="1" parent="1" source="7jQLxiFZPrQ-dQYmUEen-18" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0;entryY=0.5;entryDx=0;entryDy=0;entryPerimeter=0;endArrow=none;endFill=0;" target="7jQLxiFZPrQ-dQYmUEen-120">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-155" edge="1" parent="1" source="7jQLxiFZPrQ-dQYmUEen-17" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0;entryY=0.5;entryDx=0;entryDy=0;entryPerimeter=0;endArrow=none;endFill=0;" target="7jQLxiFZPrQ-dQYmUEen-119">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-156" edge="1" parent="1" source="7jQLxiFZPrQ-dQYmUEen-17" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0;entryY=0.5;entryDx=0;entryDy=0;entryPerimeter=0;endArrow=none;endFill=0;" target="7jQLxiFZPrQ-dQYmUEen-152">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-157" parent="1" style="verticalLabelPosition=bottom;html=1;verticalAlign=top;align=center;strokeColor=none;fillColor=#00BEF2;shape=mxgraph.azure.virtual_machine;" value="" vertex="1">
          <mxGeometry height="40" width="50" x="880" y="872.5" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-158" edge="1" parent="1" source="7jQLxiFZPrQ-dQYmUEen-157" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=1;entryY=0.5;entryDx=0;entryDy=0;entryPerimeter=0;endArrow=none;endFill=0;" target="7jQLxiFZPrQ-dQYmUEen-39">
          <mxGeometry relative="1" as="geometry">
            <Array as="points">
              <mxPoint x="905" y="705" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-159" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="Local Proxmox Server" vertex="1">
          <mxGeometry height="30" width="60" x="80" y="737.5" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-160" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="Remote Proxmox Server" vertex="1">
          <mxGeometry height="30" width="60" x="-510" y="740" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-164" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="&lt;font style=&quot;font-size: 18px;&quot;&gt;Internet&lt;/font&gt;" vertex="1">
          <mxGeometry height="30" width="60" x="-213.75" y="380" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-165" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="&lt;font size=&quot;3&quot;&gt;Remote Network&lt;/font&gt;" vertex="1">
          <mxGeometry height="30" width="60" x="-455" y="380" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-168" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="&lt;font size=&quot;3&quot;&gt;Local Network&lt;/font&gt;" vertex="1">
          <mxGeometry height="30" width="60" x="20" y="370" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-170" edge="1" parent="1" source="7jQLxiFZPrQ-dQYmUEen-122" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0.5;entryY=0;entryDx=0;entryDy=0;entryPerimeter=0;endArrow=none;endFill=0;" target="7jQLxiFZPrQ-dQYmUEen-123">
          <mxGeometry relative="1" as="geometry">
            <Array as="points">
              <mxPoint x="-600" y="680" />
              <mxPoint x="-600" y="680" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-173" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="&lt;font size=&quot;3&quot;&gt;Proxmox Simulated IAAS&lt;/font&gt;" vertex="1">
          <mxGeometry height="30" width="60" x="-710" y="370" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-180" edge="1" parent="1" source="7jQLxiFZPrQ-dQYmUEen-128" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;endArrow=none;endFill=0;">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="355" y="600" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-189" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="&lt;span style=&quot;font-size: 18px;&quot;&gt;Proxmox Simulated Enterprise Network&lt;/span&gt;" vertex="1">
          <mxGeometry height="30" width="320" x="670" y="290" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-191" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="&lt;span style=&quot;font-size: 18px;&quot;&gt;Edge&lt;/span&gt;" vertex="1">
          <mxGeometry height="30" width="60" x="610" y="430" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-192" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="&lt;span style=&quot;font-size: 18px;&quot;&gt;DMZ&lt;/span&gt;" vertex="1">
          <mxGeometry height="30" width="60" x="800" y="430" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-193" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="&lt;span style=&quot;font-size: 18px;&quot;&gt;Core&lt;/span&gt;" vertex="1">
          <mxGeometry height="30" width="60" x="960" y="430" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-194" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="&lt;span style=&quot;font-size: 18px;&quot;&gt;Access&lt;/span&gt;" vertex="1">
          <mxGeometry height="30" width="60" x="1065" y="430" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-195" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="&lt;span style=&quot;font-size: 18px;&quot;&gt;Users&lt;/span&gt;" vertex="1">
          <mxGeometry height="30" width="60" x="1215" y="430" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-197" parent="1" style="points=[[0.35,0,0],[0.98,0.51,0],[1,0.71,0],[0.67,1,0],[0,0.795,0],[0,0.65,0]];verticalLabelPosition=bottom;sketch=0;html=1;verticalAlign=top;aspect=fixed;align=center;pointerEvents=1;shape=mxgraph.cisco19.user2;fillColor=#fafafa;strokeColor=#005073;" value="" vertex="1">
          <mxGeometry height="50" width="50" x="-40" y="470" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-199" edge="1" parent="1" source="7jQLxiFZPrQ-dQYmUEen-197" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0.5;entryY=0;entryDx=0;entryDy=0;entryPerimeter=0;endArrow=none;endFill=0;" target="7jQLxiFZPrQ-dQYmUEen-95">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-201" parent="1" style="outlineConnect=0;dashed=0;verticalLabelPosition=bottom;verticalAlign=top;align=center;html=1;shape=mxgraph.aws3.vpn_connection;fillColor=#F58534;gradientColor=none;" value="" vertex="1">
          <mxGeometry height="48" width="58.5" x="-388.5" y="472.5" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-203" edge="1" parent="1" source="7jQLxiFZPrQ-dQYmUEen-201" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0.5;entryY=0;entryDx=0;entryDy=0;entryPerimeter=0;endArrow=none;endFill=0;dashed=1;dashPattern=1 4;" target="7jQLxiFZPrQ-dQYmUEen-98">
          <mxGeometry relative="1" as="geometry">
            <Array as="points">
              <mxPoint x="-359" y="685" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-204" edge="1" parent="1" source="7jQLxiFZPrQ-dQYmUEen-201" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=-0.043;entryY=0.378;entryDx=0;entryDy=0;entryPerimeter=0;endArrow=none;endFill=0;dashed=1;dashPattern=1 4;" target="7jQLxiFZPrQ-dQYmUEen-197">
          <mxGeometry relative="1" as="geometry">
            <Array as="points">
              <mxPoint x="-42" y="497" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-205" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="Workstation for Lab running Kali Linux" vertex="1">
          <mxGeometry height="30" width="60" x="25" y="480" as="geometry" />
        </mxCell>
        <mxCell id="7jQLxiFZPrQ-dQYmUEen-206" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="&lt;span style=&quot;font-size: 48px;&quot;&gt;CyberSecurity Lab&amp;nbsp;&lt;/span&gt;&lt;div&gt;&lt;span style=&quot;font-size: 48px;&quot;&gt;by Ricardo Ventura&lt;/span&gt;&lt;/div&gt;" vertex="1">
          <mxGeometry height="30" width="700" x="-130" y="170" as="geometry" />
        </mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
