# CubicBezier
A cubic bezier curve c# library
you can use this library to construct a cubic bezier curve. the library provide the follwing servies:
        public CubicBezier(float[] ctrlPt1,float[] ctrlPt2,float[] ctrlPt3,float[] ctrlPt4)
        public void Eval(float tt,ref float xx, ref float yy) //get the position at tt
        public RectangleF GetBoundingBox()
        public bool PointOnCurve(float[] P,float epsilon)  //identify whether the point on curve
        //project point to curve 
        public void ProjectPointToCurve(float[] P, ref float closestParam, ref float[] closestPos, ref float minSquareDistance)
        //evaluate 0-2 order derivatives.
        void Eval(float tt,int order,ref float[] xx,ref float[] yy)
