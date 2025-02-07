What is VXLAN?

Virtual Extensible LAN (VXLAN) is a network virtualization technology that extends Layer 2 networks over Layer 3 infrastructure. It uses encapsulation to create virtualized networks, enabling scalable and flexible data center designs.
Key Components

    VXLAN Header: Adds a 24-bit VXLAN Network Identifier (VNI) to support up to 16 million virtual networks.

    VTEP (VXLAN Tunnel Endpoint): Encapsulates and de-encapsulates VXLAN traffic, connecting physical and virtual networks.

    VNI: Identifies isolated Layer 2 segments within the overlay network.

    Underlay Network: The physical Layer 3 network carrying VXLAN traffic.

    Overlay Network: The virtual Layer 2 network created by VXLAN.

How It Works

    Encapsulates Layer 2 frames with a VXLAN header.

    Uses VTEPs to tunnel traffic over the underlay network.

    Maps VNIs to specific virtual networks for isolation.

Benefits

    Scalability: Supports millions of virtual networks.

    Flexibility: Extends Layer 2 across Layer 3 boundaries.

    Isolation: Provides secure, isolated network segments.
